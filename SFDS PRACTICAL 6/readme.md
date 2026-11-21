SFDS PRACTICAL 6

STEPS:

* Import data handling packages

* Import hypothesis testing modules

* Define the dataset endpoint

* Load the remote dataset into a DataFrame

* Inspect columns and records

* Segment evaluation ratings by gender

* Compute sample sizes and summary statistics for gender groups

* Execute Welch's independent two-sample t-test

* Bin the continuous age variable into categories

* Verify age category distributions

* Specify and fit the Ordinary Least Squares (OLS) model

* Generate the One-Way ANOVA summary table

* Build a two-way contingency table for categorical variables

* Execute the Chi-Square test of independence

* Extract continuous arrays for correlation analysis

* Compute the Pearson correlation coefficient

* Set the statistical decision threshold ( )

* Evaluate null hypotheses and print decisions


OVERVIEW:


* In this practical, statistical analysis and hypothesis testing were performed on the TeachingRatings dataset.

* Different statistical tests were used to study the relationship between teaching evaluation scores, instructor gender, age groups, tenure, and beauty scores.

* The practical also included graphical representation of data using boxplots and scatterplots to understand patterns and relationships.


OBJECTIVES:

* To understand and perform different hypothesis testing techniques.
 
* To compare teaching evaluation scores of male and female instructors.

* To analyze beauty scores across different age groups using ANOVA.
 
* To examine the relationship between tenure and gender using the Chi-Square test.
 
* To calculate the correlation between teaching evaluation scores and beauty scores.
 
* To understand p-values and statistical significance.
 
* To represent statistical results using graphs.


 OPERATIONS PERFORMED:
 
* Imported the required Python libraries for data handling and statistical analysis.
 
* Loaded the TeachingRatings dataset from an online source into a Pandas DataFrame.
 
* Inspected the dataset and displayed its first three records.
 
* Welch's Independent Two-Sample T-Test: Compared teaching evaluation scores of male and female instructors.
 
* One-Way ANOVA Test: Divided instructors into three age groups and compared their beauty scores.
 
* Created a boxplot to visualize beauty scores across different age groups.
 
* Chi-Square Test: Examined the association between instructor tenure and gender.
 
* Pearson Correlation Test: Measured the relationship between teaching evaluation scores and beauty scores.
 
* Created a scatterplot with a regression line to visualize the correlation.
 
* Compared p-values with a significance level of 0.05 to make statistical decisions.

 TECHNOLOGIES USED:
 
* Python: Programming language used for statistical analysis.
 
* Google Colab: Cloud-based platform used to write and execute Python code.
 
* Pandas: Used for loading, handling, and manipulating dataset records.
 
* NumPy: Used for numerical operations.
 
* SciPy: Used to perform t-tests, Chi-Square tests, and Pearson correlation.
 
* Statsmodels: Used for Ordinary Least Squares (OLS) regression and ANOVA.
 
* Matplotlib: Used for creating graphs.
 
* Seaborn: Used for creating boxplots and regression plots.

 DATASET:
 
* Dataset Name: TeachingRatings

* Dataset Source: AER (Applied Econometrics with R)

* Dataset Link: https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv

* The dataset contains information about university instructors, including:
 
* Gender
 
* Age
 
* Teaching evaluation scores

* Beauty scores
 
* Tenure status
 
* Number of students
 
* Course division

* Credits
 
* The dataset was used to perform statistical tests and identify relationships between different instructor-related variables.


 FILES:

* TeachingRatings.csv: Dataset loaded from the online source for performing statistical analysis.

 Conclusion:
 
* In this practical, I successfully performed different statistical hypothesis tests using Python on the TeachingRatings dataset.
 
* Welch's t-test showed a statistically significant difference between male and female instructors' teaching evaluation scores.
 
* One-Way ANOVA showed significant differences in beauty scores across different age groups.
 
* The Chi-Square test showed no significant association between tenure and gender.
 
* Pearson correlation showed a weak but statistically significant positive relationship between teaching evaluation scores and beauty scores.

* Through this practical, I learned how to perform hypothesis testing, interpret p-values, make statistical decisions, and visualize data using different graphs.

* It improved my understanding of statistical analysis and its practical applications.


