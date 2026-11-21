SFDS PRACTICAL 5

STEPS:

* import the required libraries

* load the dataset

* check the dataset information

* find the total number of observations

* count evaluation scores greater than 4.5

* calculate the probability for q1

* filter the scores between 3.5 and 4.2

* count the scores between 3.5 and 4.2

* calculate the probability for q2

* write the given values for q3

* state the hypotheses

* calculate the standard error

* calculate the z-score

* calculate the two-tailed p-value

* make the final decision

OVERVIEW:


* In this practical, we performed statistical analysis on the TeachingRatings dataset using Python in Google Colab.

* We calculated probabilities for different teaching evaluation scores and performed a Two-Tailed Z-Test to determine whether a sample mean is significantly different from a given population mean.


OBJECTIVES:

* To import the required Python libraries.
 
* To load and understand the TeachingRatings dataset.
 
* To calculate the probability of evaluation scores greater than 4.5.
 
* To calculate the probability of evaluation scores between 3.5 and 4.2.
 
* To understand and perform a Two-Tailed Z-Test.

* To calculate standard error, Z-score and p-value.
 
* To make statistical decisions using a significance level of 0.05.

 OPERATIONS PERFORMED:
 
* Imported the required libraries: Pandas, NumPy and SciPy.
 
* Loaded the TeachingRatings dataset using its CSV URL.
 
* Displayed the first five rows and checked the dataset columns.
 
* Calculated the total number of observations.
 
* Counted evaluation scores greater than 4.5 and calculated their probability.
 
* Filtered evaluation scores between 3.5 and 4.2 and calculated their probability.
 
* Performed a Two-Tailed Z-Test using the given population and sample values.
 
* Calculated standard error, Z-score and p-value.
 
* Compared the p-value with the significance level of 0.05.
 
* Made the final decision regarding the null hypothesis.

 TECHNOLOGIES USED:
 
* Python: Programming language used for statistical calculations.
 
* Google Colab: Platform used to write and execute Python code.
 
* Pandas: Used for loading and handling the dataset.

* NumPy: Used for numerical calculations.
 
* SciPy: Used for calculating the p-value in the Z-Test.

 DATASET:
 
* Dataset Name: TeachingRatings
 
* Source: Rdatasets – AER TeachingRatings

* Dataset Link: https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv

* The dataset contains information about teachers, including age, gender, beauty, teaching evaluation scores, tenure, students and other related attributes.

* The eval column was mainly used for probability calculations.

 FILES:
 
 
* TeachingRatings.csv: Dataset loaded directly from the online CSV source.

CONCLUSION:

* In this practical, we learned how to calculate probabilities using a real-world dataset and perform a Two-Tailed Z-Test using Python.
 
* We found that 17.06% of teaching evaluation scores were greater than 4.5, while 35.42% were between 3.5 and 4.2.

* In the Z-Test, the p-value was 0.1561, which is greater than the significance level of 0.05. 

* Therefore, we failed to reject the null hypothesis. This practical helped us understand probability, hypothesis testing and statistical analysis using Python.

