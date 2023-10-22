# OasisInternship_Task1_IrisDataSet

This project aims to develop machine learning models to classify iris flowers into three species: Iris setosa, Iris versicolor, and Iris virginica. The Iris dataset is a classic dataset available on Kaggle. The dataset is evaluated on the basis of Machine Learning's classification algorithms.

The project code is located in the irisdatasetproject1.py file. This file imports the Iris dataset from scikit-learn and trains three machine learning models: Logistic Regression, K-Nearest Neighbor, and Decision Tree Classifier. The models are then evaluated on a held-out test set.

STEP BY STEP OVERVIEW : 

The first step in any machine learning project is to prepare the data. In this project, the data is preprocessed by performing the following steps:
*Checking for Inconsistency in Data
* EDA
* Splitting Data
* Machine Learning Algorithms
* Performance Comparison of ML Algorithms

  RESULTS/ANALYSIS:
Once the data is preprocessed, the machine learning models are trained. In this project, three different machine learning models are trained:

* Logistic Regression: A simple but effective classification algorithm. It works by fitting a logistic function to the data, which can then be used to predict the probability of each class. The accuracy was 100%.
  
* K-Nearest Neighbor (KNN): KNN  works by finding the K most similar instances in the training data to the new instance being classified. The class of the new instance is then predicted based on the classes of the K most similar instances. The accuracy was 93%

* Decision Tree Classifier: Decision Tree Classifiers are a type of tree-based machine learning algorithm. It work by building a tree of decision rules, which can then be used to predict the class of a new instance. The accuracy was 96%.

The results were analyzed through classification report and confusion metrics from sklearn library.

Conclusion

This project has demonstrated how to use machine learning to classify iris flowers into three species. The project has also shown how to compare the performance of different machine learning models.
