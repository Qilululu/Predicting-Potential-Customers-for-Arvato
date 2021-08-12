# Capstone Project Proposal, Machine Learning Engineer

This repository contains associated data files and tools for deploying my machine learning model for capstone project.

## Inputs and Evaluation Data
 
All of the private data is from AZ Direct GmbH data for my sole use, 

**Input Data**
* Features of data for the general population in Germany; 891 211 persons (rows) x 366 features (columns).
* Features of data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).


**Evaluation Data and Competition Data**

* Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns). 
It is used for testing the precision of training model.
* Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
This group of data have no results, and is used for Kaggle Competition.

## Technology Tools

My project is conducted in Uadicty VM workpalce and my local computer workplace, and my tools are all from python packages.

**Udaicty VM Workplace and Local Workplace**
*I did most of the project here, from preprocessing data, researching data to conducting PCA, unsupervised learning and supervised learning.
*I use my local workplace to do hyperparamter tunning to promote efficiency.

**Python Packages**
*I simply use pandas, numpy and so on to compute and process data.
*I use sklearn, specificly preprocessing methods, PCA, and Kmeans to finish unsupervised learning and utilize XGBoost to build supervised learning model.



