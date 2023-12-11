# NN-Group-Project-Team-14
Here is a breakdown and a guide to all the files used in the project.

CNN_pri.ipynb is the file that contains all of the CNN and Transfer Learning used in our project. It shows examples of preprocessing and model summaries as well as accuracy.

Cifar_10_CNN_Project.ipynb shows a test of the baseline CNN architecture that we were studying in our project without the data augmentation used in the paper.

Final_Ensemble_Classification shows the stacking ensemble used in our paper. It models the optimal XGboost and k-NN models learned from our testing and optimization loops. It then loads in the CNN prediction probabilities from CNN_pri.ipynb. Then, it creates a meta learner that is train and tested.

PCA_of_Cifar_10_And_KNN is the script that created and tested the PCA on the data. Also, it is where the optimal number of k-NN neighbors were identified with an associated PCA number of components. 

Random Forest is the script that created and tested the Random Forest Classifier. The Random Forest Classifier is also optimized in this script for the number of estimators.

XGBoost is the script that created and tested the XGBoost Classifier. The XGBoost Classifier is also optimized in this script for the number of estimators.

Cnn_reshaped_array.npy and Cnn_reshaped_array_test_predictions.npy are the prediction probablities of the CNN in Cnn_pri
