# Week 3: Introduction to Machine Learning 

![GitHub stars](https://img.shields.io/github/stars/SalmanKhan3/ML-Internship-B01?style=social)
![GitHub forks](https://img.shields.io/github/forks/SalmanKhan3/ML-Internship-B01?style=social)
![Internship](https://img.shields.io/badge/ML%20Internship-B01-red)
![MIT License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![GitHub Repo Size](https://img.shields.io/github/repo-size/SalmanKhan3/ML-week2)

##  📘 Description
### In this repository i have documented task if week 3 of my machine learinig internship.I have implemented simple linear regression  purely in python,make prediction method that predict new data and calculate R square manually.I have train multiple regression on claifornia hosuing data set and calculate mean absolute error (MAE), mean square error (MSE),root mean square error (RMSE) and r square score. In task 3.3 i have implemented Polynomail regression with different degree i.e 1,3,5 and 10. Plot actual value and regression line.Plot all model on same graph to visualize underfitting and overfitting. In taks 3.4 I have trained plynomail regrssion and save model uisng pickle,joblib and json.Load the model and print file size and time for loading.

## 📑 Table of Contents
- [Task 3.1: Simple Linear Regression from Scratch (4 hours)](#Simple-Linear-Regression-from-Scratch) <br>
- [Task 3.2: Multiple Linear Regression with sklearn (3 hours)](#Multiple-Linear-Regression-with-sklearn) <br>
- [Task 3.3: Polynomial Regression & Overfitting (4 hours)](#Polynomial-Regression-&-Overfitting) <br>
- [Task 3.4: Model Persistence - Saving & Loading (2 hours)](#Model-Persistence)

## Task 3.1: Simple Linear Regression from Scratch (4 hours)

1.  create class called LinearRegressionScratch. 
2.  Implement gradient descend algorithm in fit method.
3.  create predict method to predict new data.
4.  calulate r square score
5.  Plot data and regrssion line
6. Plot cost and number of iteration
## Implement LinearRegrssionScratch class
!['linear-regrssion scratch'](screenshots/Screenshot%20(163).png) <br> <br> <br>
## Define dependent and independent varaible and fit the model <br> <br> <br>
!['linear-regrssion scratch'](screenshots/Screenshot%20(164).png) <br> <br> <br>
## Predict new data, calculate R square score and plot actual data and regression line. <br> <br> <br>
!['linear-regrssion scratch'](screenshots/Screenshot%20(165).png) <br> <br> <br>
# Task 3.2: Multiple Linear Regression with sklearn (3 hours) <br> <br> <br>
## In this task i have loaded california housing data set trained multiple regression on it and calculate MAE, MSE, RMSE and r2 score. <br> <br> <br>
1.  Load data set and check for null values. <br> <br> <br>
!['Multiple regression'](screenshots/Screenshot%20(166).png) <br> <br> <br>
2. Calculate Corelation and draw sns heatmap to visusalize correlation. <br> <br> <br>
!['correlation'](screenshots/Screenshot%20(167).png) <br> <br> <br>
3. Split dataset. <br> <br> <br>
!['split data set'](screenshots/Screenshot%20(168).png) <br> <br> <br>
4. Train multiple regression, make prediction and calculate diiferent metrics. <br> <br> <br>
!['train_model'](screenshots/Screenshot%20(169).png) <br> <br> <br>
5. Plot actual data and regrssion line <br> <br> <br>
!['plot'](screenshots/Screenshot%20(171).png) <br> <br> <br>

# Task 3.3: Polynomial Regression & Overfitting (4 hours)  <br> <br> <br>
## In this task iave implemented Polynomail regression using degree 1,2,3,5 and 10 and identify underfiting and overfitting.Plot actual data point and regression line.Plot all model on same graph. Plot learinig curve of each model.
1. Fit linear Regression <br> <br> <br>
!['linear-regression'](screenshots/Screenshot%20(172).png) <br> <br> <br>
2. Fit polynomail regrssion with dgree 2. print model weights.make new predictions. <br> <br> <br>
!['Poly regression'](screenshots/Screenshot%20(173).png)  <br> <br> <br>
3. Plot 3rd degree Polynomail. <br> <br> <br>
![''](screenshots/Screenshot%20(175).png)
4. plot all model on same graph and calculate training and testing error. <br> <br> <br>
![''](screenshots/Screenshot%20(176).png) <br> <br>
## Table showing errors for each degree  <br> <br>
<table border="1" cellpadding="8" cellspacing="0"> 
  <thead>
    <tr>
      <th>Degree</th>
      <th>Train MSE</th>
      <th>Test MSE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>0.230156678</td>
      <td>0.317962888</td>
    </tr>
    <tr>
      <td>2</td>
      <td>0.224718633</td>
      <td>0.290678892</td>
    </tr>
    <tr>
      <td>3</td>
      <td>0.073689653</td>
      <td>0.092421277</td>
    </tr>
    <tr>
      <td>5</td>
      <td>0.073148923</td>
      <td>0.099644493</td>
    </tr>
    <tr>
      <td>10</td>
      <td>0.072338691</td>
      <td>0.106363916</td>
    </tr>
  </tbody>
</table>

# Overfitting and ubderfitting
Low train + high test error → Overfitting (Degree 5,10)  <br> <br>
High train + high test error → Underfitting (degree 1 and 2)  <br> <br>
Balanced low errors → Good fit (Degree 3)  <br> <br>
<br><br>

# Task 3.4: Model Persistence - Saving & Loading (2 hours)
In this task I have trained 3rd degree polynomail and save the model usind pickle, joblib and json.
Then load the model in another notebook and prit file size in kb and print loading time using time module.
1. Define X and y and plot data points
![''](screenshots/Screenshot%20(177).png) <br> <br>
2. Save model and model weights. <br> <br>
![''](screenshots/Screenshot%20(178).png) <br> <br>
3. Create anather notebook and laod the model. <br> <br> <br>
![''](screenshots/Screenshot%20(179).png) <br> <br> <br>
4. print file size and loading time. <br> <br> <br>
![''](screenshots/Screenshot%20(180).png) <br>





