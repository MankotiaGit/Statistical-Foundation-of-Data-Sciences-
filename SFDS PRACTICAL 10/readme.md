SFDS PRACTICAL 10

STEPS:

* Import the required libraries, including numpy, pandas, matplotlib, seaborn, and scikit-learn.

* Set the visualization style using seaborn.

* Load the built-in wine dataset using load_wine().

* Convert the dataset into a pandas dataframe with appropriate feature names.

* Add target labels and wine class names to the dataframe.

* Store all feature names for further analysis.

* Display the first five rows of the dataset using df.head().

* Check the number of rows and columns using df.shape.

* Count the number of samples belonging to each wine class.

* Calculate descriptive statistics such as mean, standard deviation, minimum, and maximum.

* Create boxplots to compare the distribution of each feature across wine classes.

* Identify possible outliers and differences in feature distributions using boxplots.

* Create a scatter plot to visualize the relationship between flavanoids and proline.

* Calculate the covariance matrix of the original features.

* Visualize the covariance matrix using a heatmap.

* Standardize the features using StandardScaler.

* Create a new dataframe containing the standardized feature values.

* Display the statistical summary of the standardized data to verify scaling.

* Calculate and visualize the covariance matrix of the standardized features.

* Apply principal component analysis (PCA) to reduce the dataset to two principal components.

* Calculate and display the explained variance ratio of PC1 and PC2.

* Calculate the total percentage of variance explained by the two principal components.

* Create a new dataframe containing PC1, PC2, and the corresponding wine class labels.

* Plot the original features (alcohol and malic acid) to compare wine classes.

* Plot PC1 against PC2 to visualize the wine classes after dimensionality reduction.

* Display the percentage of variance explained by each principal component on the plot axes.

* Apply PCA to all standardized features to calculate the explained variance of every component.
  
* Calculate the cumulative explained variance for all principal components.

* Plot cumulative explained variance against the number of components.

* Analyze the plots to understand how PCA reduces dimensionality while retaining important information and helps visualize differences between wine classes.

OVERVIEW:

* In this practical, we performed data analysis and dimensionality reduction using the Wine dataset. 

* The dataset contains chemical properties of different wines belonging to three classes.

* We used statistical methods and visualizations to understand the data, identify patterns, and compare wine classes.

* We also applied feature standardization and Principal Component Analysis (PCA) to reduce the number of dimensions while retaining important information.

OBJECTIVES:

* To import and understand the Wine dataset.
 
* To perform basic statistical analysis of the dataset.
 
* To visualize feature distributions using boxplots and scatterplots.

* To calculate and visualize covariance matrices.
 
* To standardize the dataset using StandardScaler.
 
* To understand relationships between different wine features.
 
* To apply PCA for dimensionality reduction.
 
* To visualize wine classes using principal components.

OPERATIONS PERFORMED:

* Imported the required Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.
 
* Loaded the built-in Wine dataset using load_wine().
 
* Converted the dataset into a Pandas DataFrame and added wine class labels.

* Displayed the first five rows and checked the dataset dimensions.
 
* Calculated descriptive statistics, including mean, standard deviation, minimum, and maximum.
 
* Created boxplots to compare alcohol distribution across different wine classes.
 
* Created a scatterplot to visualize the relationship between flavanoids and proline.
 
* Calculated and visualized the covariance matrix using a heatmap.
 
* Standardized the features using StandardScaler.
 
* Calculated and visualized the covariance matrix of standardized features.
 
* Applied Principal Component Analysis (PCA) to reduce the dataset into three principal components.
 
* Calculated the explained variance ratio and created a 3D scatterplot to visualize the distribution of wine classes.

TECHNOLOGIES USED:

* Python: Main programming language.
 
* Google Colab: Platform used to write and execute Python code.
 
* NumPy: Used for numerical calculations.
 
* Pandas: Used for data manipulation and analysis.
 
* Matplotlib: Used for creating graphs and visualizations.
 
* Seaborn: Used for statistical visualizations and heatmaps.
 
* Scikit-learn: Used for loading the dataset, standardization, and PCA.

DATASET:

* Dataset Name: Wine Dataset

* Source: Built-in Scikit-learn dataset (load_wine()).

* The Wine dataset contains 178 samples belonging to three different wine classes and 13 numerical features.

* Some features included in the dataset are:

* Alcohol
 
* Malic Acid

* Ash
 
* Magnesium
 
* Total Phenols
 
* Flavanoids
 
* Color Intensity
 
* Hue
 
* Proline
 
* Dataset Shape: 178 rows × 15 columns (including target and class labels).

* Class Distribution:
 
* Class 0: 59 samples
 
* Class 1: 71 samples
 
* Class 2: 48 samples

FILES:

* The following files and libraries were used in this practical:

* Wine Dataset: Built-in dataset imported from Scikit-learn.
 
* NumPy: Numerical operations.
 
* Pandas: Data handling and analysis.
 
* Matplotlib and Seaborn: Data visualization.
 
* Scikit-learn: StandardScaler and PCA implementation.

CONCLUSION:

* In this practical, we successfully performed data analysis and dimensionality reduction using the Wine dataset.

* We learned how to calculate descriptive statistics, visualize data using different graphs, calculate covariance matrices, and standardize features. 

* We also applied Principal Component Analysis (PCA) to reduce the dataset into three principal components.

* The first three principal components explained approximately 66.5% of the total variance (PC1 = 36.2%, PC2 = 19.2%, and PC3 = 11.1%).

* The 3D scatterplot helped us understand the distribution and separation of the three wine classes.

* Overall, this practical helped us understand data preprocessing, visualization, standardization, and dimensionality reduction techniques.
