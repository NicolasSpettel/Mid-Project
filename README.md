# Ironhacks Mid-Project 

## Answering question about an Animal Welfare Center and predicting time spent at the shelter using regression models

The goal of this project is to work with an unfamiliar dataset and perform the usual data analysis steps and ultimatly present the project in the Ironhack workspace. 
The dataset was titled "Animal Welfare Center" and was found on kaggle.com.
In order to create a regression model with moderate scores and for ethic reasons we decided to focus on only three outcome types present in the dataset. This reduced the size of the dataset to almost half. Afterwards the usual data cleaning and eda steps were taken. 
One example: the breed and color columns had so many different values that we had to combine the smaller ones into a bigger category.
After achieving rather low r2-scores with linear regression ond standard scaler, we had diffculties select the right features for our model.
It was clear that our data did not follow a linear pattern. Consquently we used the PolynomialFeatures transformation to help the model.

## Table of Contents
1. Reading and reducing dataset to desired size.
2. Data cleaning
3. Data exploration
4. Feature Engineering
4.1. Outlier Analysis
4.2. Feature selection
5. Model scores
6. Conclusion
7. Confidence intervals

## This project was worked on and created by Nidhal Saoudi and Nicolas Spettel
