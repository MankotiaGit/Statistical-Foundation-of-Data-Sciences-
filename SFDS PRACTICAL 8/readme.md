SFDS PRACTICAL 8

STEPS:

* Install the required Python libraries for data analysis, visualization, and machine learning.
 
* Import NumPy, Pandas, Matplotlib, and Seaborn for calculations, data handling, and visualization.
 
* Import Scikit-learn functions for splitting data, creating the Decision Tree, and evaluating the model.
 
* Set the Seaborn plotting style and configure Pandas to display all columns.
 
* Load the Pima Indians Diabetes dataset and assign proper names to all columns.
 
* Check the shape of the dataset to find the number of rows and columns.
 
* Display the first five rows to understand the structure of the dataset.
 
* Check the dataset information, including data types and non-null values.
 
* Generate a statistical summary of the numerical data using describe() .
 
* Check for zero values in important health-related columns that may represent missing or invalid values.
 
* Separate the dataset into features (X) and the target variable (y) and check the class distribution.
 
* Split the data into 75% training data and 25% testing data using stratified sampling.
 
* Create a Decision Tree Classifier using the Entropy criterion with a maximum depth of 4.
 
* Train the Decision Tree model using the training data and make predictions on the test data.
 
* Evaluate the model using accuracy, classification report, and confusion matrix
 
* Display the confusion matrix as a heatmap to compare actual and predicted results.
 
* Visualize the complete Decision Tree to understand how the model makes predictions.
 
* Define functions to calculate Entropy and Gini Index for the target values.
 
* Calculate the Information Gain and Weighted Gini for each feature using its median as the split threshold.
 
* Create a table comparing the Information Gain and Weighted Gini values of all features.
 
* Identify the feature with the highest Information Gain and compare it with the actual root feature selected by Scikit-learn.
 
* Calculate the feature importance values from the trained Decision Tree.

* Display the feature importances using a bar chart and print their numerical values.

OVERVIEW:

* This practical focuses on analysing the Pima Indians Diabetes dataset and building a Machine Learning model using the Decision Tree Classification algorithm.

* The main objective is to predict whether a person has diabetes or not based on health-related features such as glucose level, blood pressure, insulin, BMI, age, and pregnancies.

* The practical also explores Entropy, Gini Index, Information Gain, and feature importance to understand how a Decision Tree makes predictions.

OBJECTIVES:

* To load and analyse the Pima Indians Diabetes dataset.
 
* To understand the structure and statistical properties of the dataset.
 
* To identify zero values that may represent missing or invalid health data.
 
* To divide the dataset into training and testing sets.
 
* To implement a Decision Tree Classifier using the Entropy criterion.

* To predict diabetes outcomes and evaluate model performance.
 
* To visualize the Decision Tree and confusion matrix.
 
* To calculate Entropy, Gini Index, and Information Gain.
 
* To identify the most important features for diabetes prediction.

OPERATIONS PERFORMED:

* Installed and imported the required Python libraries.
 
* Loaded the Pima Indians Diabetes dataset from an online source.
 
* Checked the dataset shape, first five records, information, and statistical summary.
 
* Checked zero values in important columns such as Glucose, BloodPressure, SkinThickness, Insulin, and BMI.
 
* Separated the independent features (X) and dependent target variable (y).
 
* Divided the dataset into 75% training data and 25% testing data using stratified sampling.
 
* Created and trained a Decision Tree Classifier using Entropy with a maximum depth of 4.
 
* Predicted diabetes outcomes using the testing dataset.
 
* Evaluated the model using accuracy, classification report, and confusion matrix.
 
* Visualized the confusion matrix using a heatmap.
 
* Visualized the Decision Tree with different maximum depths of 4, 10, and 15.
 
* Defined functions to calculate Entropy and Gini Index.
 
* Calculated Information Gain and Weighted Gini for each feature using median values as split thresholds.
 
* Compared Information Gain values and identified the feature with the highest Information Gain.
 
* Calculated and analysed feature importance.

* Result:

* The Decision Tree model achieved 75% accuracy on the testing dataset.
  
* Glucose was identified as the feature with the highest Information Gain and was also selected as the actual root feature by Scikit-learn.


TECHNOLOGIES USED:

* Python: Main programming language.
 
* Google Colab: Platform used to write and execute the code.
 
* NumPy: Used for numerical calculations.
 
* Pandas: Used for dataset loading and manipulation.
 
* Matplotlib: Used for data visualization.
 
* Seaborn: Used for heatmaps and graphical representation.
 
* Scikit-learn: Used for Decision Tree implementation, data splitting, prediction, and model evaluation.
 
* Graphviz: Installed as a supporting visualization library.

DATASET:

* Dataset Name: Pima Indians Diabetes Dataset

* Source: Online GitHub dataset.

* Dataset Link: https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

* The dataset contains 768 rows and 9 columns, including 8 independent features and 1 target variable.

* Column	Description

* Pregnancies -	Number of pregnancies

* Glucose -	Glucose level

* Blood Pressure -	Blood pressure

* Skin Thickness -	Skin thickness

* Insulin -	Insulin level

* BMI -	Body Mass Index

* Diabetes Pedigree Function -	Diabetes history-related function

* Age -	Age of the person

* Outcome -	Diabetes prediction (0 or 1)

* The target variable represents:

* 0: No Diabetes
  
* 1: Diabetes

FILES:

* The following files and resources were used in this practical:

* Pima Indians Diabetes Dataset: Online CSV file used for analysis and prediction.
  
* Visualizations: Confusion matrix heatmap and Decision Tree diagrams generated during execution.

CONCLUSION:

* In this practical, we successfully analysed the Pima Indians Diabetes dataset and implemented a Decision Tree Classification model to predict diabetes outcomes.

* We performed data exploration, checked zero values, divided the dataset into training and testing sets, and evaluated the model using different performance metrics.

* The model achieved 75% accuracy. We also studied Entropy, Gini Index, and Information Gain to understand how the Decision Tree selects features for splitting.

* Glucose was identified as the most important feature for the initial split.

* Overall, this practical helped us understand the working of Decision Tree Classification and its application in healthcare-related predictions.

