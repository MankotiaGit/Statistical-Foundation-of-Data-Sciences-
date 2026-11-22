SFDS PRACTCIAL 7

STEPS:

* Load the teaching ratings dataset using pandas
 
* Import pandas, numpy, statsmodels, and scipy libraries for data analysis
 
* Create a female dummy variable where female is represented by 1 and male by 0
 
* Display the first few rows of the dataset using df.head()
 
* Select female as the independent variable and eval as the dependent variable

* Add a constant to the independent variable for the intercept
 
* Perform an OLS regression to study the relationship between gender and teaching evaluation
 
* Display the regression summary containing coefficients, p-value, R-squared, and other statistics
 
* Divide the age variable into three groups using pd.cut()
 
* Label the three age groups as Young, Middle, and Old
 
* Use beauty as the dependent variable and age_group as the categorical independent variable
 
* Fit an OLS model to examine the relationship between age group and beauty
 
* Generate an ANOVA table using the fitted OLS model
 
* Select beauty as the independent variable and eval as the dependent variable for regression analysis

* Perform an OLS regression to examine the relationship between beauty and teaching evaluation
 
* Calculate the Pearson correlation coefficient and p-value between beauty and eval to measure their linear relationship
  

 OVERVIEW:
 
* In this practical, we performed statistical analysis on the TeachingRatings dataset using Python.
  
* The main objective was to study the relationship between gender, age, beauty scores, and teaching evaluation scores of instructors.
  
* We applied Ordinary Least Squares (OLS) regression, ANOVA, and Pearson correlation to understand the relationships between different variables and interpret the statistical results.

 OBJECTIVES:
 
* To load and explore the TeachingRatings dataset.
 
* To create a dummy variable for gender (female = 1, male = 0).
 
* To perform OLS regression to analyse the relationship between gender and teaching evaluation.
 
* To divide instructors into three age groups: Young, Middle, and Old.
 
* To perform ANOVA to examine the relationship between age groups and beauty scores.
 
* To perform regression analysis between beauty scores and teaching evaluation.
 
* To calculate the Pearson correlation coefficient and p-value.

OPERATIONS PERFORMED:

* Imported the required Python libraries such as Pandas, NumPy, Statsmodels, and SciPy.
 
* Loaded the TeachingRatings dataset using Pandas.
 
* Created a female dummy variable, assigning 1 to females and 0 to males.
 
* Displayed the first five rows of the dataset using df.head().
 
* Performed OLS regression using gender as the independent variable and evaluation score as the dependent variable.
 
* Divided instructor ages into three groups using pd.cut().
 
* Applied OLS regression to study the relationship between age groups and beauty scores.
 
* Generated an ANOVA table to analyse differences in beauty scores among age groups.
 
* Performed OLS regression using beauty scores as the independent variable and evaluation scores as the dependent variable.

* Calculated the Pearson correlation coefficient and p-value between beauty and evaluation scores.

TECHNOLOGIES USED:

* Python: Main programming language used for statistical analysis.
 
* Google Colab: Cloud-based platform used to write and execute Python code.
 
* Pandas: Used for loading and handling the dataset.
 
* NumPy: Used for numerical operations.
 
* Statsmodels: Used for OLS regression and ANOVA analysis.
 
* SciPy: Used to calculate Pearson correlation and p-value.

DATASET:

* Dataset Name: TeachingRatings

* Source: AER (Applied Econometrics with R)

* Dataset Link: TeachingRatings Dataset

* The dataset contains information about instructors, including:

* Age
  
* Gender
 
* Beauty score
 
* Teaching evaluation score
 
* Minority status
 
* Credits
 
* Division
 
* Tenure
 
* Number of students
 
* Professor ID
 
* The dataset contains 463 observations used in the statistical analysis.

FILES USED:

* TeachingRatings.csv: Dataset loaded directly from the online CSV source.
  
* Libraries: Pandas, NumPy, Statsmodels, and SciPy.

CONCLUSION:

* In this practical, we successfully performed statistical analysis on the TeachingRatings dataset using regression, ANOVA, and correlation techniques.

* We found that gender has a statistically significant relationship with teaching evaluation scores, with a female coefficient of -0.1680.

* ANOVA showed significant differences in beauty scores among different age groups.

* The Pearson correlation coefficient between beauty and teaching evaluation was 0.1890, indicating a weak positive relationship.

* Overall, this practical helped us understand how statistical methods can be used to analyse relationships between variables and interpret real-world data.
