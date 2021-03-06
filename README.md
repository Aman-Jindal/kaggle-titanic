# Getting started in Data Science with Kaggle competition:Titanic dataset

In this tutorial we will be exploring and analysing the Titanic [dataset](https://www.kaggle.com/c/titanic/data) which is available on [kaggle](https://www.kaggle.com). This tutorial will provide you a basic approach towards understanding the data. We will proceed with small steps with me explaining each step then build upon these to make conclusions. It is a perfect turorial for those who are new to data science and wants to enter into a kaggle competition after completing an online course. So Let's get started.

## Overview of the Competition

### Description

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

### Objective

Our objective is to predict if a passenger is survived or not. But we are not limited to this we will explore the data in depth to find more information.

### Evaluation

In this competition your model(with which you are trying to predict) will be evaluated by the metrics accuracy which is (Number of corrected prediction)/(Total number of predictions). We will be looking at other metrics also to evaluate our model.

### Submission

The file needs to be submitted in csv format.

The file should have exactly 2 columns:

* PassengerId (sorted in any order)
* Survived (contains your binary predictions: 1 for survived, 0 for deceased)

| PassengerId | Survived |
| ---------- | --------- |
| 892 | 0 |
| 893 | 1 |
| 894 | 0 |
| . | . |

For more information about competition go [here.](https://www.kaggle.com/c/titanic#description)

## Plan of Action

Our plan of action is laid out in these following tasks:

#### 1. Understanding the Data

In this we will load our data and then clean our data to reveal its mysteries we will do these using python libraries numpy and pandas. Then we will find our dependent and independent variables, identify their types, missing data and much more.

#### 2. Exploratory Data Analysis

It is quite clear with the name itself. In this we will find the patterns(aka mysteries) in each variables using our wand seaborn.

#### 3. Predictions using Machine Learning

In this we will use Logistic Regression to predict the number of passengers who survived. There will be lot of fine tuning of the   model for better predictions. 

#### 4. Evaluation

Finally, we will evaluate the model using cross-validation(K-fold) and validation set approach(train-test-split).

You can check out all the action here.



