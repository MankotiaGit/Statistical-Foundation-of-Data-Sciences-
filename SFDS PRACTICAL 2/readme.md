SFDS PRACTCIAL 2

STEPS:

* Import required libraries- pandas is used for data handling and analysis.NumPy is used for numerical operations.

* Load the Dataset- the dataset is loaded directly from the given URL. It is stored in a Pandas DataFrame named df.

* Display First 10- this displays the first 10 rows of the dataset. It helps us understand the structure and type of data.

* Check Dataset Information-df.info() displays the number of rows, columns, data types, and non-null values. df.columns displays all column names.

* Select Students Column- the students column is selected from the dataset. It is stored in a separate variable for analysis.

* Find Mean- the mean gives the average number of students. It is calculated by adding all values and dividing by the number of observations.

* Find Median- the median gives the middle value of the students data when then values are arranged in ascending order.

* Find Minimum and Maximum- min() finds the smallest value, while max() finds the largest value in the students column.

* Descriptive Statistics- this provides important statistical measures such as count, mean, standard deviation, minimum, quartiles, and maximum.

* Create Histogram- a histogram is created to show the distribution of beauty scores. The data is divided into 15 intervals called bins.

* Add Labels and Display Graph- labels and a title are added to the histogram. plt.show() displays the final graph.

* Mean Beauty Score by Gender- the data is grouped according to gender. The average beauty score is then calculated separately for each gender.

* Standard Deviation by Gender- This calculates the standard deviation of beauty scores for each gender. It shows how much the scores vary within each group.

* Gender and Tenure Crosstab- A cross-tabulation table is created between gender and tenure. It shows the number of teachers in each category.

* Percentage Analysis- This converts the gender-tenure counts into percentages. normalize="index" calculates the percentages separately within each gender.


OVERVIEW:

* In this practical, we performed statistical data analysis on the TeachingRatings dataset using Python in Google Colab. 

* The dataset contains information about professors, including their age, gender, beauty ratings, teaching evaluation scores, tenure status, and number of students.

* The main purpose of this practical was to understand the dataset, calculate basic statistical measures, analyze beauty scores, and compare different categories of professors using data analysis techniques and graphical representations.

OBJECTIVES:

* To understand and analyze the TeachingRatings dataset.
 
* To identify whether the dataset is cross-sectional or time-series data.
 
* To calculate mean, median, minimum, and maximum values.
 
* To perform descriptive statistical analysis.
 
* To visualize the distribution of beauty scores using a histogram.
 
* To compare average beauty scores based on gender.
 
* To calculate the standard deviation of beauty scores for male and female professors.
 
* To analyze the relationship between gender and tenure status.
 
* To understand data analysis using Python libraries.

 OPERATIONS PERFORMED:
 
* Importing Libraries: Imported Pandas, NumPy, and Matplotlib for data handling, numerical calculations, and visualization.

* Loading Dataset: Loaded the TeachingRatings dataset from the given URL into a Pandas DataFrame.

* Displaying First 10 Rows: Used head(10) to display the first ten records of the dataset.

* Checking Dataset Information: Used info() and columns to identify the number of rows, columns, data types, and column names.

* Identifying Data Type: Identified the dataset as cross-sectional data because it contains observations of different professor/course combinations at a single point in time.

* Calculating Basic Statistics: Calculated the mean, median, minimum, and maximum values of the students column.

* Descriptive Statistics: Used describe() to calculate count, mean, standard deviation, minimum, maximum, and quartile values.

* Creating Histogram: Created a histogram to visualize the distribution of beauty scores and calculated skewness.

* Mean Beauty Score by Gender: Grouped the data according to gender and calculated the average beauty score.

* Standard Deviation by Gender: Calculated the standard deviation of beauty scores separately for male and female professors.

* Gender and Tenure Analysis: Created a cross-tabulation table to compare the number of male and female professors according to tenure status.

* Percentage Analysis: Converted the gender and tenure counts into percentages to compare tenure rates between male and female professors.


 TECHNOLOGIES USED:

* Technology	Purpose
 
* Python	Programming language
 
* Google Colab	Writing and executing Python code
 
* Pandas	Data handling and statistical analysis
 
* NumPy	Numerical operations
 
* Matplotlib	Data visualization
 
* TeachingRatings Dataset	Data source

 DATASET:
 
* Dataset Name: TeachingRatings

* Dataset URL: https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv

* The TeachingRatings dataset contains information related to professors and their teaching evaluations.
 
* Total Rows: 463
 
* Total Columns: 13
 
* Missing Values: No missing values were found in the displayed dataset information.
 
* Important columns include:
 
* age – Age of the professor.
 
* gender – Gender of the professor.
 
* beauty – Beauty rating score.

* eval – Teaching evaluation score.
 
* tenure – Tenure status.
 
* students – Number of students.
 
* allstudents – Total number of students.
 
* division – Course division.
 
* Some important results obtained:
 
* Statistical Measure	Result
 
* Mean students	36.62
 
* Median students	23
 
* Minimum students	5
 
* Maximum students	380
 
* Mean beauty score (Female)	0.1161
 
* Mean beauty score (Male)	-0.0845

* Tenured female professors	74.36%
 
* Tenured male professors	80.60%

 FILES USED:
 
* TeachingRatings.csv: Dataset downloaded directly from the given URL and loaded into the notebook.
 
* beauty_histogram.png: Histogram image generated to visualize the distribution of beauty scores.

 CONCLUSION:
 
* In this practical, we successfully performed statistical analysis on the TeachingRatings dataset using Python and Google Colab.
 
* We calculated basic statistical measures such as mean, median, minimum, maximum, and standard deviation.
 
* We also created a histogram to understand the distribution of beauty scores and compared beauty ratings and tenure status based on gender.

* The analysis showed that female professors had a slightly higher average beauty score, while male professors had a higher tenure percentage in the dataset.

* We also learned how to use Pandas, NumPy, and Matplotlib for data analysis and visualization.
 
* Overall, this practical helped us understand the basics of statistical analysis, data interpretation, and graphical representation using Python.

 
