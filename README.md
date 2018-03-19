# Breast-cancer-Prediction

The data set is taken from Wisconsin breast cancer diagnostic data. The attributes in the dataset are :

1) ID number
2) Diagnosis (M = malignant, B = benign)

Features of the cell :
1) radius 
2) texture 
3) perimeter
4) area
5) smoothness 
6) compactness 
7) concavity 
8) concave points 
9) symmetry
10) fractal dimension 

The data set is first loaded and the unwanted columns such as 'id' and 'unnamed' are dropped.
The diagnosis value M and B are coverted to binary as 1 and 0 respectively.
Visualised the data with respect to 0 or 1 based on each feature.
The data is then split into training and test set and a model is fit using 10-fold cross validation.
The model is then trained using various classification algorithms - logistic regression, decision tree classifier, k nearest neighbour, random forest, Support vector machine, and Naive bayes. 

It is found that SVM gives the maximum accuracy among all with 97.6% in predicting which cell is malignant based on the top 5 features. 
