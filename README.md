# Parameter_Optimization_of_SVM
This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken a dataset and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

We used the Scikit-learn library in Python to implement our SVM model and optimize its parameters. The dataset we used for this project was Mushroom Data Set. After splitting the dataset into 10 random samples, we trained and tested our SVM model using various parameter combinations.

The final result of our project is a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. This table can be used as a reference for future classification problems that require SVM parameter optimization.

Feel free to explore the code and results in this repository, and please let us know if you have any questions or feedback.

# Dataset Description
dataset
This is data that confirmed the grade of performance with age and some exercise performance data.

columns
data shape : (13393, 12)

age : 20 ~64
gender : F,M
height_cm : (If you want to convert to feet, divide by 30.48)
weight_kg
body fat_%
diastolic : diastolic blood pressure (min)
systolic : systolic blood pressure (min)
gripForce
sit and bend forward_cm
sit-ups counts
broad jump_cm
class : A,B,C,D ( A: best) / stratified
