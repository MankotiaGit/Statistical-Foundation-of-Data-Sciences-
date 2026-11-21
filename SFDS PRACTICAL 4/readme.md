SFDS PRACTICAL 4

STEPS:

* import the libraries

* load the dataset

* display the dataset information

* find duplicate professors

* find total number of observations

* find number of unique instructors

* calculate average age

* calculate standard deviation of age

* keep one observation for each instructor

* check the number of observations after filtering

* calculate average age after filtering

* calculate standard deviation after filtering

* calculate average evaluation by division

* create bar chart

* calculate correlation

* create scatterplot

* create a figure for two plots

* filter female instructors

* create male scatterplot

* adjust and display the plots

* create figure

* loop through gender

* loop through tenure

* filter data using gender and tenure

* select marker according to tenure

* create the scatterplot

* add axis labels

* add title

* display legend

* display the graph

OVERVIEW:

* In this practical, we performed data analysis and visualization using the TeachingRatings dataset in Python.

* The main purpose was to study the relationship between instructors' age, gender, tenure, and teaching evaluation scores. 

* We also identified duplicate records, calculated statistical measures, and created different graphs to understand the data.


OBJECTIVES:

* To import and load the TeachingRatings dataset.
 
* To identify duplicate records using the professor ID.
 
* To calculate the total number of observations and unique instructors.
 
* To calculate the mean and standard deviation of instructors' ages.
 
* To remove duplicate instructor records.
 
* To calculate average teaching evaluations by course division.
 
* To study the relationship between age and teaching evaluation.
 
* To compare teaching evaluation scores based on gender and tenure.
 
* To visualize the results using different graphs.

 OPERATIONS PERFORMED:
 
* Imported the required Python libraries.
 
* Loaded the TeachingRatings dataset using Pandas.
 
* Displayed the dataset information and first five records.
 
* Identified duplicate records using the prof column.
 
* Calculated the total observations (463) and unique instructors (94).
 
* Calculated the average age and standard deviation.
 
* Removed duplicate instructor records and calculated the statistics again.
 
* Calculated average teaching evaluation scores for lower and upper divisions.
 
* Created a bar chart to compare average evaluations by division.
 
* Calculated the correlation between instructor age and evaluation score.
 
* Created a scatterplot with a regression line for age versus evaluation.
 
* Created separate scatterplots for male and female instructors.

* Compared age and evaluation scores based on gender and tenure.
 
* Added titles, labels, markers, legends, and regression lines to improve graph presentation.

 TECHNOLOGIES USED:
 
* Technology	Purpose
 
* Python	Programming language
 
* Google Colab	Writing and executing Python code
 
* Pandas	Data loading and manipulation
 
* NumPy	Numerical calculations and regression lines
 
* Matplotlib	Data visualization and graph creation

 DATASET:
 
* Dataset Name: TeachingRatings

* Dataset Source: AER – TeachingRatings

* Dataset Link: https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv

* Dataset Description:

* The TeachingRatings dataset contains information about university instructors, their teaching characteristics, and student evaluation scores.
 
* Total observations: 463
 
* Total columns: 13
 
* Unique instructors: 94
 
* Important columns used:
 
* prof: Professor identification number.
 
* age: Age of the instructor.
 
* gender: Gender of the instructor.
 
* tenure: Tenure status.
 
* eval: Teaching evaluation score.
 
* division: Course division (lower or upper).
 
* students: Number of students.

 FILES USED:
 
 
* TeachingRatings.csv – Dataset loaded directly from the online AER repository.

 CONCLUSION:
* In this practical, we successfully performed data analysis and visualization on the TeachingRatings dataset using Python.

* We identified duplicate instructor records, calculated statistical measures, and compared teaching evaluation scores across different course divisions.

* We also created bar charts and scatterplots to understand the relationship between instructors' age, gender, tenure, and teaching evaluation scores. 

* The correlation between age and evaluation was approximately -0.052, indicating a very weak negative relationship.

* Overall, this practical helped us understand data cleaning, statistical analysis, correlation, and graphical representation using Pandas, NumPy, and Matplotlib in Google Colab.
