SFDS PRACTICAL 12

STEPS:

* Import the required libraries for implementing the Metropolis Algorithm.
 
* Define the energy function and initialize the starting value, temperature and iterations.
 
* Generate new random values and calculate the energy difference.
 
* Accept or reject the new values based on energy and probability.
 
* Display the final value and minimum energy.
 
* Initialize the starting population to 100 and set the growth rate to 10%.
 
* Define the number of time steps as 10 years and display the initial population.
 
* Calculate the new population by applying the fixed growth rate.
 
* Repeat the calculation using a loop for 10 years.
 
* Display the population growth for each year.

OVERVIEW:

* This practical focuses on implementing two mathematical models using Python: the Metropolis Algorithm and the Deterministic Model.

* The Metropolis Algorithm is used to find the minimum value of a function using random values and probability, while the Deterministic Model is used to calculate population growth over 10 years using a fixed growth rate of 10%.

OBJECTIVES:

* To understand and implement the Metropolis Algorithm using Python.
 
* To find the minimum energy of a given function.
 
* To understand the concept of probabilistic algorithms.
 
* To implement a Deterministic Model for population growth.
 
* To calculate population growth over 10 years using a fixed growth rate.
 
* To understand the difference between probabilistic and deterministic models

OPERATIONS PERFORMED:

Part A: Metropolis Algorithm

* Imported the required Python libraries, Random and Math.
 
* Defined an energy function as \(E(x) = x^2\).
 
* Initialized the starting value as 5, temperature as 1.0 and iterations as 1000.

* Generated new random values within a given range.
 
* Calculated the energy difference between old and new values.
 
* Accepted or rejected new values based on energy difference and probability.
 
* Displayed the final value and minimum energy.
 
Output:

* Final value of x: 0.28513

* Minimum energy: 0.0813
  
Part B: Deterministic Model

* Initialized the starting population as 100.
 
* Set the annual growth rate to 10%.
 
* Defined the number of time steps as 10 years.
 
* Applied the fixed growth rate to calculate the new population.
 
* Used a loop to repeat the calculation for 10 years.
 
* Displayed the population growth for each year.
 
Final Output:

* Initial Population: 100
 
* Population after 10 years: 259.37

TECHNOLOGIES USED:

* Python: Programming language used to implement both models.
 
* Google Colab: Cloud-based platform used to write and execute Python code.
 
* Random Library: Used to generate random values in the Metropolis Algorithm.
 
* Math Library: Used to calculate exponential probability.
 
* Loops and Conditional Statements: Used for repeated calculations and decision-making.

DATASET:

No external dataset was used in this practical.

* Part A: Used randomly generated values and the mathematical energy function \(E(x) = x^2\).
 
* Part B: Used an initial population of 100 and a fixed annual growth rate of 10% to calculate population growth over 10 years.

FILES:

* Part A: Metropolis Algorithm implementation.
 
* Part B: Deterministic Model implementation.

CONCLUSION:

* In this practical, I successfully implemented the Metropolis Algorithm and Deterministic Model using Python in Google Colab.

* I learned how the Metropolis Algorithm uses random values and probability to find the minimum energy of a function. 

* I also understood how a Deterministic Model works using fixed inputs and rules to calculate population growth. 

* The practical helped me understand the working of probabilistic and deterministic models and their applications in mathematical modelling and data analysis.
