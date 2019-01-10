# QDA-on-Breast-Cancer-dataset
Quadratic Discriminant Analysis on Breast Cancer Dataset

**Dataset description:**

Number of Predictor Variables : 30
Target variable : 1 (Diagnosis with class labels 'malignant' and 'benign') 

For detailed description of the data,Please go through "http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names"

As this dataset came as a part of scikit learn in-built datasets, i'm gonna use that data for prediction.

**Approach:**

1.Split the dataset into 80:20 ration for train and test purpose

2.Apply QDA(Quadratic Discriminant Analysis) on train data and use the trained model to predict the target variable of Test Data

Achieved 99% Accuracy on test data after applying QDA
