# Project-Abalone

# Predicting the Age of Abalone using Machine Learning and Neural Networks

#### Group NoFloods: 
* Amit Patel
* Daniah Al Bayati
* Roopa Patel
* Samuel Parks
* Steven Lee

Presented on: `August 18, 2020`

## Introduction
What is an abalone? From Wikipedia, an abalone is a common name for any of a group of small to very large sea snails, marine gastropod molluscs in the family Haliotidae. Determining the age of abalone is typically time consuming - requiring cutting the shell, staining it, then counting the number of rings with a microscope.  We want to see if physical measurements can be used to predict the age.

## Dataset 
The data for the project comes from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Abalone

* There are 4,177 rows in the dataset with 8 attributes:
  * 1 Categorical
    * Sex: Values of (M)ale, (F)emale, (I)nfant
  * 6 Continuous:
 * Length (mm): the longest shell measurement
    * Diameter (mm): perpendicular to length
    * Height (mm): with meat in shell
    * Whole Weight (g): whole abalone
    * Viscera Weight (g): gut weight after bleeding
    * Shell Weight (g): after being dried
  * 1 Integer
    * Rings: Note that Age of the Abalone in years = Rings + 1.5 

## Project Goal
The goal of this project is to find the best ML and NN model to predict the number of Rings (directly related to age). This is a Supervised Learning ML challenge where Rings can be treated as a discrete (Classification) or continuous (Regression) problem.


![](Images/image1.PNG)

* Machine Learning Models Used
  * Linear Regression Models
    * scikit-learn LinearRegression
    * scikit-learn Ridge
    * scikit-learn LASSO
    * scikit-learn ElasticNet    
  * Classification Models
    * scikit-learn LogisticRegression
    * scikit-learn KNN
    * scikit-learn RandomForest
    * scikit-learn SVM
  * H2O AutoML
  
* Neural Network Models Used
  * Regression Models
    * Simple
    * Deep
  * Classification Models
    * Simple
    * Deep

