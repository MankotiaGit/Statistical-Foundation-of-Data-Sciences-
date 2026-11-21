SFDS PRACTCIAL 3 

STEPS:

* Import Libraries (These libraries are used for data handling, numerical calculations, statistical analysis, and visualization.)

* Load the Dataset (The Student Rating dataset is loaded from the given URL and the first five rows are displayed.)

* Select Minority Professors (This filters the dataset to include only visible-minority professors.)

* Calculate Percentage (This calculates the percentage of minority professors who are tenured.)

* Display Result (This displays the percentage rounded to two decimal places.)

* Test Whether Tenure Differs (The chi-square test checks whether minority status and tenure status are significantly associated.)

* Group Professors by Tenure (This separates professors into tenured and untenured groups based on their tenure status.)

* Calculate Mean and Standard Deviation (This calculates the average age and standard deviation for both tenure groups.)

* Display Separately (This displays the mean and standard deviation of age separately for tenured and untenured professors.)

* Select Age Variable (The age column is selected from the dataset for visualization.)

* Create Histogram (A histogram is created to show the distribution of professors' ages.)

* Add Labels (Labels and a title are added to make the graph easy to understand.)

* Display Graph (The histogram is displayed because age is a numerical continuous variable.)

* Difference Between pyplot.bar() and pyplot.barh() (plt.bar() uses vertical bars, whereas plt.barh() uses horizontal bars.)

* Count Genders (This counts the number of professors in each gender category.)

* Create Bar Graph (A vertical bar graph is created using the gender counts.)

* Add Labels (Axis labels and a title are added to the gender graph.)

* Display Graph (This displays the gender distribution graph.)

* Select Tenured Professors (This filters the dataset to include only tenured professors.)

* Select Evaluation Scores (The evaluation scores of tenured professors are selected.)

* Calculate Median (The median evaluation score is calculated for the tenured professors.)

* Display Result (This displays the calculated median evaluation score.)

OVERVIEW:


* In this practical, we performed statistical analysis and data visualization on the TeachingRatings dataset using Python in Google Colab.

* The practical focuses on analysing professors' age, gender, minority status, tenure status, and evaluation scores.

* Different statistical operations and graphical representations were used to understand the dataset and interpret the results.

OBJECTIVES:

* To load and explore the TeachingRatings dataset.
 
* To calculate the percentage of visible minority professors who are tenured.
 
* To compare the average age of tenured and untenured professors.

* To understand the age distribution using a histogram.
 
* To analyse the gender distribution of professors using bar graphs.
 
* To calculate the median evaluation score of tenured professors.
 
* To understand the difference between vertical and horizontal bar graphs.

 OPERATIONS PERFORMED:
 
* Imported the required Python libraries such as Pandas, NumPy and Matplotlib.
 
* Loaded the TeachingRatings dataset using its URL.
 
* Displayed the first five rows and checked the dataset dimensions.
 
* Filtered visible minority professors and calculated the percentage who were tenured (84.38%).

* Calculated the mean and standard deviation of age separately for tenured and untenured professors.
 
* Created a histogram to represent the age distribution of professors.
 
* Calculated descriptive statistics such as count, mean, standard deviation, minimum, maximum and skewness of age.
 
* Counted male and female professors.
 
* Created vertical and horizontal bar graphs using plt.bar() and plt.barh().
 
* Filtered tenured professors and calculated their median evaluation score.


 TECHNOLOGIES USED:

 
* Python: Programming language used for statistical analysis.
 
* Google Colab: Cloud-based platform used to write and execute Python code.
 
* Pandas: Used for loading, filtering, grouping and analysing data.
 
* NumPy: Used for numerical operations.
 
* Matplotlib: Used for creating histograms and bar graphs.

 DATASET:
 
* Dataset Name: TeachingRatings Dataset

* Dataset Source: AER (Applied Econometrics with R)

* Dataset URL:
 
* https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv

* Dataset Description:

* The TeachingRatings dataset contains information about professors, including their age, gender, minority status, tenure status, beauty ratings, evaluation scores and number of students.
 
* Total observations: 463

* Total columns: 13
 
* Important columns used:
 
* minority – Indicates whether a professor belongs to a visible minority group.
 
* age – Age of the professor.
 
* gender – Gender of the professor.

* tenure – Indicates tenure status.
 
* eval – Teaching evaluation score.
 
* students – Number of students taught.

 FILES USED:
 
* TeachingRatings.csv: Dataset loaded directly from the given online URL.
 
* age_histogram.png: Histogram generated to represent the age distribution of professors.

 CONCLUSION:
 
 * In this practical, we successfully performed statistical analysis and data visualization on the TeachingRatings dataset using Python.
 
 * We calculated percentages, mean, standard deviation and median values.
 
 * We also created histograms and vertical and horizontal bar graphs to understand the distribution of professors based on age and gender.
 
 * The practical helped us understand how Python libraries such as Pandas, NumPy and Matplotlib can be used for data analysis, statistical calculations and graphical representation of data.
 
 * It also improved our understanding of handling real-world datasets and interpreting statistical results.
