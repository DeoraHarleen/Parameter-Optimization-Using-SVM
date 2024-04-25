# Parameter-Optimization-Using-SVM
Optimization of parameter values means finding the best combination of the parameters that governs the model, to enable it to perform the given task with relative accuracy. The hyperparameters tuned in the SVM model were:-

Parameters--Description

kernel--the type of kernel used for the SVM

c (epsilon)--penalty parameter of the error term

degree (nu)--the degree of the polynomial kernel

# Dataset used
The dataset used for the project is Room Occupancy Estimation that has been downloaded from the UCI Machine Learning Repository.

Number of Instances: 10129
Number of Attributes: 16

This code optimizes Support Vector Machine (SVM) parameters for a given dataset and visualizes the convergence of the model's accuracy over iterations. It performs the following steps:

1. Loads a dataset named 'Occupancy_Estimation.csv'.
2. Drops unnecessary columns ('Date' and 'Time').
3. Visualizes the distribution of the target variable.
4. Prepares the feature matrix (`X`) and target vector (`y`).
5. Splits the dataset into training and testing sets.
6. Standardizes the feature matrix.
7. Conducts a random search for the best SVM hyperparameters (kernel, C, and gamma) using nested loops and a fitness function.
8. Stores the results in a DataFrame.
9. Identifies the sample with the highest accuracy.
10. Computes and plots the learning curve to visualize model convergence.
