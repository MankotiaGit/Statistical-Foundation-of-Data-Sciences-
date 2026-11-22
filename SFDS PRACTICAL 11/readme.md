SFDS PRACTCIAL 11

STEPS:

* Installing the required libraries.

* Importing the necessary libraries.

* Loading and cleaning the sunspot dataset.

* Plotting sunspot data over the years.

* Creating 12-year solar cycles.

* Fitting the Gamma distribution.

* Plotting the histogram of sunspot counts.

* Comparing observed data with the Gamma distribution.

* Defining the Gamma model and performing MCMC sampling.

* Visualising the first 50, all and last 50 MCMC samples.

* Removing burn-in samples.

* Plotting trace graphs and histograms of parameters a and b.

* Checking MCMC convergence.

* Estimating the parameters a and b.

* Predicting future sunspot counts.

* Visualising the predicted sunspot distribution.

OVERVIEW:

* In this practical, we analysed historical sunspot data using statistical methods and probability distributions.

* The main objective was to understand the pattern of sunspot activity over time and predict future sunspot counts using the Gamma distribution and Markov Chain Monte Carlo (MCMC) sampling.

* We collected monthly sunspot data from 1749 to 2018, cleaned the dataset, visualised sunspot activity, fitted a Gamma distribution, and used Bayesian modelling to estimate parameters and make future predictions.

OBJECTIVES:

* To load and analyse historical sunspot data.
 
* To clean and prepare the dataset for statistical analysis.

* To visualise monthly sunspot activity over the years.
 
* To create 12-year solar cycles.
 
* To fit a Gamma probability distribution to sunspot counts.
 
* To perform MCMC sampling for parameter estimation.
 
* To check MCMC convergence using trace plots and histograms.
 
* To predict future sunspot counts using posterior predictive sampling.

OPERATIONS PERFORMED:

* Installing Libraries: Installed the required PyMC and ArviZ libraries.

* Importing Libraries: Imported NumPy, Pandas, Matplotlib, SciPy, PyMC and ArviZ.

* Loading Dataset: Loaded monthly sunspot data from the SILSO website.

* Data Cleaning: Removed missing and invalid values and converted date columns into the correct format.

* Data Visualisation: Created a time-series graph to display sunspot activity from 1749 to 2018.

* Creating Solar Cycles: Divided the dataset into 12-year solar cycles.

* Gamma Distribution Fitting: Fitted a Gamma distribution to the positive sunspot counts and estimated its shape and scale parameters.

* Histogram Plotting: Created histograms to understand the distribution of sunspot counts.

* MCMC Sampling: Built a Bayesian Gamma model and performed MCMC sampling to estimate parameters a and b.

* Burn-in Removal: Removed the first 1000 samples to improve parameter estimation.

* Convergence Checking: Used trace plots, histograms and ArviZ summaries to check MCMC convergence.

* Future Prediction: Used posterior predictive sampling to estimate future sunspot counts and visualised the predicted distribution.

TECHNOLOGIES USED:

* Google Colab: Used to write and execute Python code.
 
* Python: Main programming language.
 
* NumPy: Used for numerical calculations and array operations.
 
* Pandas: Used for loading, cleaning and handling dataset.
 
* Matplotlib: Used for creating graphs and visualisations.
 
* SciPy: Used for fitting and analysing the Gamma distribution.
 
* PyMC: Used for Bayesian modelling and MCMC sampling.
 
* ArviZ: Used for analysing MCMC samples and checking convergence.

DATASET:

* Dataset Name: Monthly Sunspot Number Dataset

* Source: SILSO – Sunspot Index and Long-term Solar Observations

* Dataset Link: https://www.sidc.be/SILSO/DATA/SN_m_tot_V2.0.csv

* The dataset contains monthly sunspot observations from January 1749 to November 2018.

* Total observations after cleaning: 3,239
 
* Time period: 1749–2018
 
* Important columns: Year, Month, Date, Sunspots, Std, Observations and Indicator.
 
* The dataset was used to study historical solar activity and predict future sunspot counts.

FILES USED:

* Sunspot Dataset (SN_m_tot_V2.0.csv): Historical monthly sunspot data downloaded directly from the SILSO website.

CONCLUSION:

* In this practical, we successfully analysed historical sunspot data using the Gamma distribution and MCMC sampling. 

* We performed data cleaning, visualisation, distribution fitting, Bayesian parameter estimation and future prediction.

* The MCMC analysis estimated the mean values of parameter a as approximately 1.177 and parameter b as approximately 71.478.

* The predicted future sunspot count had a mean of approximately 83.72.

* We also learned how probability distributions and Bayesian methods can be used to analyse real-world time-series data and make predictions. 

* This practical helped us understand statistical modelling, parameter estimation and predictive analysis using Python.
