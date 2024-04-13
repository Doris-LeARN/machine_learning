## Classification 

Scikit-learn is an open-source machine learning library.
It features various classification, regression and clustering algorithms such as support vector machines (SVM), random forests, k-means clustering.

This library is maintened by INRA, a French Reseach Lab. Scikit-learn v1 was release in 2010 and as of today is considered to be one of the best framework to getting started with Machine Learning

**IRIS FLOWER DATASET**

The dataset consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris
versicolor).
For each sample, you have the length and the width of the petals, in centimeters.

Classification is the task of classifying the elements of a dataset into groups on the basis of a classification
rule.

In this exemple we want to find the line that divide the data so that all elements from one category are on
one side of the line

**MULTI-CLASS CLASSIFICATION**

During the first day you created one binary classifier for each kind of Iris.
What if you had an algorithm that can detect as many category as you want from the ground-up ?

**Task01**

1 - Create only one classifier to detect all Iris species at the same time using KNeighborsClassifier from Scikit-learn

2 - Plot the decision boundaries of your model. Compare it from the one from LinearSVC, is it better ?

3 - Display the performance indicators of your model : precision score, recall score and confusion matrix

4 - Try different values of the hyper-parameter K (the number of neighbors) to get the better score. Which value is best ?


**DECISION TREES**

Decisions trees is a very different approach.
Rather than thinking mathematical with lines or clusters for dividing the dataset, Decision Trees are based on how a human would do it, by asking questions.

**Task02**

1 - Create one decision tree classifier to detect all Iris species at the same time using DecisionTreeClassifier from Scikit-learn

2 - Display the tree as PNG image. What do you understand ? Using a basic plot of the dataset do the questions asked make sense ?

3 - Plot the decision boundaries of your model. Compare it from the one from LinearSVC and KNeighborsClassifier, which one is better ?

4 - Display the performance indicators of your model : precision score, recall score and confusion matrix

5 - Try differents values of the hyper-parameter max_depth (the depth of the three) to get better score.
Which value is best ?