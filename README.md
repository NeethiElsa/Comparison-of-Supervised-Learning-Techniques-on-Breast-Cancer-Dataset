# Comparison-of-Supervised-Learning-Techniques-on-Breast-Cancer-Dataset
To evaluate and compare the performance of different classification algorithms, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), and k-Nearest Neighbors (k-NN), on the Breast Cancer dataset to identify the most effective model for accurate breast cancer diagnosis.

Using the Breast Cancer dataset from scikit-learn, which contains features related to tumor characteristics and a binary target (benign or malignant), we performed various classification alogorithms to predict whether a tumor is malignant or benign based on the provided features.

After loading the data, we applied some preprocessing steps before applying the classification models.There were no null values present in the dataset.We applied Standard scaling since the data had features that were in different ranges.By applying standard scaling, we ensure that all features contribute equally and are on same scale.This gives better performance as well.

Post scaling of the data, we applied different classification algorithms, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), and k-Nearest Neighbors (k-NN), on the Breast Cancer dataset.

The report based on the F1 score came  as below.
            Model            F1-Score
3    Support Vector Machine  0.978055
0       Logistic Regression  0.963192
2  Random Forest Classifier  0.955368
4                       KNN  0.955368
1  Decision Tree Classifier  0.941988

From the analysis, we have come to a conclusion that SVM is the best model for this dataset since we have a F1 score of 0.978 and Decison Tree Classifier is the worst model for this dataset with F1 score of 0.94.
