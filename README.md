# Steel-Plate-Failure-Prediction
Prediction of steel faults based on different attributes and parameters

## Objective:
The objective of the project is to classify the different types of steel faults based on different attributes and parameters. The end goal is to predict the fault type by training the model with different machine learning algorithms.In doing so I have applied to use two approaches- **Supervised learning** and **unsupervised learning**.
In **Supervised** learning I trained the model with the training data along with their corresponding output(well labelled).
Used different algorithms below to analyse how they perform compared to one other.I have employed **Gaussian Naïve Bayes Classifier**,**Logistic Regression**,**SVM**,**LDA**,**KNN**,**DECISION TREE**,**Random Forest**.I have used **PCA** for reducing the features and applied **K Means** as an expample of **unsupervised learning**.
Finally, I  compare the models and see how well each model perform using Classification metrics: Confusion Matrix, Precision, Recall and F-1 Score in **validation set** and **Test set**

## Motivation:
A fault may be defined as an unacceptable difference of at least one characteristic property or attribute of a system from acceptable usual typical performance. The main purpose of any fault diagnosis system is to determine the location and occurrence time of possible faults on the basis of accessible data and knowledge about the performance of diagnosed processes. Manual fault diagnosis system is the traditional way where an expert with electronic meter tries to obtain some information about relevant operational equipment, check the maintenance manual and then diagnose the probable causes of a particular fault. However, intelligent fault diagnosis techniques can provide quick and correct systems that help to keep product quality problems at bay and facilitates precautionary maintenance.
This project evaluates the performances of several popular and effective data mining models to diagnose seven commonly occurring faults of the steel plate namely; Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps and Other_Faults.



