## Binary Classification
Scikit-learn is an open-source machine learning library. It features various classification, regression and clustering algorithms such as support vector machines (SVM), random forests, k-means clustering.

This library is maintened by INRA, a French Reseach Lab. Scikit-learn v1 was release in 2010 and as of today is considered to be one of the best framework to getting started with Machine Learning 

**IRIS FLOWER DATASET**

The dataset consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). For each sample, you have the length and the width of the petals, in centimeters.  !

Classification is the task of classifying the elements of a dataset into groups on the basis of a classification rule.

In this exemple we want to find the line that divide the data so that all elements from one category are on one side of the line 

## Task

As the dataset has 3 category (Iris Setosa, Iris Versicolor and Iris Virginica), you can’t use only one binary
classifier, you must create three differents ones :
- one for : “is this Iris Setosa” ? The algorithm answsers True or False
- another one for “is this Iris Versicolor” ? The algorithm answsers True or False
- and the last one for “is this Iris Virginica” ? The algorithm answsers True or False

For each Iris species :

1 - Create a binary classifier to detect this kind of Iris using LinearSVC from sklearn.

2 - Plot the decision boundaries of your model.

3 - Display the performance indicators of your model : precision score, recall score, confusion matrix and
ROC Curve

4 - Use StandardScaler to standardize the dataset as a preprocessing step, do you have better scores ?

5 - Try different values of the hyper-parameter C (margin separating the two support vectors) to get the
better score. Which value is best ?

When you finished the task take a look to “OneVsRestClassifier” from Scikit-learn 