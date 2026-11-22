SFDS PRACTICAL 9

STEPS:

OVERVIEW:

* In this practical, we implemented the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset.

* The main purpose was to classify different species of Iris flowers based on their sepal length, sepal width, petal length, and petal width.

* We performed Exploratory Data Analysis (EDA), feature scaling, model training, prediction, and accuracy evaluation.

* We also compared different K values to find the best value for improving model performance.

OBJECTIVES:

* To understand and implement the K-Nearest Neighbors (KNN) algorithm.
 
* To load and explore the Iris dataset.
 
* To perform EDA using head(), describe(), and groupby().
 
* To divide the dataset into training and testing sets.
 
* To perform feature scaling using StandardScaler.
 
* To train the KNN classification model.
 
* To evaluate the model using a confusion matrix and classification report.
 
* To compare error rates for K values from 1 to 20.
 
* To identify the best K value and calculate final accuracy.
 
* To visualize the classification results.

OPERATIONS PERFORMED:

* Importing Libraries: Imported NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn libraries.
 
* Loading Dataset: Loaded the Iris dataset and converted it into a Pandas DataFrame.
 
* Exploratory Data Analysis: Used head(), describe(), and groupby() to understand the dataset and calculate statistical information.
 
* Data Splitting: Divided the dataset into 80% training data and 20% testing data.

* Feature Scaling: Applied StandardScaler to standardize the features.
 
* Model Training: Trained the KNN classifier using K = 5.
 
* Model Evaluation: Calculated accuracy and generated a confusion matrix.
 
* Classification Report: Calculated precision, recall, F1-score, and support.
 
* Error Rate Comparison: Tested K values from 1 to 20 and calculated their error rates.
 
* Data Visualization: Plotted the error rate against K values and visualized the test results.
 
* Best K Selection: Identified K = 1 as the best value based on the lowest error rate.
 
* Final Model: Trained the final KNN model using K = 1.

TECHNOLOGIES USED:

* Python: Main programming language.
 
* Google Colab: Cloud-based platform used to write and execute Python code.
 
* NumPy: Used for numerical calculations.
 
* Pandas: Used for data handling and analysis.
 
* Matplotlib: Used for creating graphs and visualizations.
 
* Seaborn: Used for confusion matrix visualization.
 
* Scikit-learn: Used for dataset loading, feature scaling, KNN model training, and model evaluation.

DATASET:

* Dataset Name: Iris Dataset

* The Iris dataset is a built-in dataset available in the Scikit-learn library. It contains 150 records of Iris flowers belonging to three different species:
 
* Setosa
 
* Versicolor
 
* Virginica
 
* Dataset Features:

* Sepal Length (cm)
 
* Sepal Width (cm)
 
* Petal Length (cm)
 
* Petal Width (cm)
 
* Dataset Details:

* Total Records: 150
 
* Total Features: 4
 
* Total Classes: 3
 
* Training Records: 120
 
* Testing Records: 30
 
* Missing Values: 0

FILES USED:

* Iris Dataset: Built-in dataset loaded using Scikit-learn.
 
* Output Graphs: Confusion matrix, error rate vs K value graph, and KNN test results visualization.

CONCLUSION:

* In this practical, we successfully implemented the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset.

* We performed data analysis, feature scaling, model training, and evaluation. Initially, the model trained with K = 5 achieved an accuracy of 93.33%.

* After comparing K values from 1 to 20, we found that K = 1 provided the lowest error rate and the best accuracy of 96.67%.

* This practical helped us understand how the KNN algorithm works and how selecting an appropriate K value can improve classification performance.
 
