 SFDS FINAL PRACTICAL 

STEPS:

 * Import the required libraries.

 * Generate the dataset of 500 students.

 * Display the dataset and class distribution.

 * Fit Logistic Regression using Statsmodels.

 * Display the model summary and odds ratios.

 * Split the data into training and testing sets (70:30).

 * Train the Logistic Regression model using Scikit-learn.

 * Predict results and calculate accuracy.

 * Display the confusion matrix.

 * Plot the ROC curve and calculate AUC.

 * Find the threshold for at least 85% recall for the fail class.

 * Display the confusion matrix at the selected threshold.

 * Predict the pass probability for a student with 5 study hours and 60% attendance.

 * Interpret the odds ratios and compare the thresholds.

Overview:

 * This practical implements Logistic Regression to predict whether students will pass or fail based on their study hours and attendance.

Objectives:

* To understand Logistic Regression.

* To predict student pass/fail outcomes.

* To evaluate model performance using accuracy, confusion matrix, ROC curve, and AUC.

* To identify students at risk of failing.

Operations Performed:

* Generated a dataset of 500 students.

* Fitted Logistic Regression using Stats models.

* Calculated odds ratios.

* Split the dataset into training and testing sets.

* Trained and tested the model using Scikit-learn.

* Calculated accuracy and confusion matrix.

* Plotted the ROC curve and calculated AUC.

* Selected a threshold for at least 85% recall for the fail class.

* Predicted the pass probability of a new student.

Technology Used:

* Python

* Google Colab / Jupyter Notebook

* NumPy

* Pandas

* Matplotlib

* Seaborn

* Stats models

* Scikit-learn

Dataset:

* A randomly generated dataset containing 500 student records with three attributes:

 * hours: Weekly study hours
 
 * attendance: Attendance percentage
 
 * passed: Pass/fail status (1 = Passed, 0 = Failed)

 Files:
 
* Dataset generated within the notebook.

Conclusion:

* Logistic Regression was successfully implemented to predict student pass/fail outcomes. 

* The model was evaluated using accuracy, confusion matrix, ROC curve, and AUC.

* A suitable threshold was selected to identify students at risk of failing, demonstrating the usefulness of Logistic Regression in student performance prediction.

Follow-up questions:

1. Interpret the odds ratios for one extra study hour and for one extra percent of
attendance.

* The odds ratio for study hours is approximately 1.3063.

* This means that for every one-hour increase in weekly study time, the odds of passing increase by approximately 30.63%, assuming attendance remains constant.

* The odds ratio for attendance is approximately 1.0823.

* This means that for every one-percent increase in attendance, the odds of passing increase by approximately 8.23%, assuming study hours remain constant.

* Both odds ratios are greater than 1, indicating that study hours and attendance have a positive relationship with the odds of passing the examination.

2. Compare the default 0.5 threshold with your chosen threshold. Which would you use
for an early-warning system, and what is the cost of the extra false alarms?

  * At the default threshold of 0.5:

   Actual Fail (0) and Predicted Fail (0) is 55 
   Actual Fail (0) and Predicted Pass (1) is 17

   Actual Pass (1) and Predicted Fail (0) is 12
   Actual Pass (1) and Predicted Pass (1) is 66

  * At the chosen threshold of approximately 0.425:

   Actual Fail (0)	and Predicted Fail (0) is 62
   Actual Fail (0) and Predicted Pass (1) is 10

   Actual Pass (1) and Predicted Fail (0) is 15	
   Actual Pass (1)	and Predicted Pass (1) is 63                                                             

* The chosen threshold identifies more failing students correctly. The recall for the fail class increases from approximately 76.39% to 86.11%.

* For an early-warning system, I would prefer the chosen threshold because the main objective is to identify students who are likely to fail before the examination.

* However, the lower threshold also increases false alarms. At the default threshold, 12 students who actually pass are incorrectly flagged as failing. At the chosen threshold, this number increases to 15.

* The cost of these extra false alarms is that some students who would pass may receive unnecessary warnings, counselling, or additional academic support. This requires extra time and resources from teachers and the university.

* Despite this cost, I would use the chosen threshold because missing a student who is genuinely at risk of failing may be more serious than giving additional support to a student who eventually passes.
