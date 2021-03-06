# Machine Learning Engineer Nanodegree

## Capstone Proposal
Arwa alquhayz - 12-2021

## Domain Background
The World Development Indicators (WDI) is the World Bank's most comprehensive collection of cross-country development data.
The World Development Indicators is a collection of data on global development and poverty reduction that are relevant, high-quality, and internationally comparable. The database comprises 1,400 time series indicators for 217 economies and more than 40 nation groupings, with many of the indicators having data going all the way back more than 50 years.

The Happy Planet Index is a measure of sustainable wellbeing that ranks countries based on how effectively they use limited natural resources to produce long, happy lives.
We need it because multiple crises, such as persistent inequalities, accelerating climate breakdown, and rapid biodiversity loss, are interconnected and stem from the same root cause: our economies are structured, governed, and measured to promote short-term economic growth over long-term collective wellbeing. Governments frequently place faster economic growth above all other considerations. They lose sight of what really matters: people living long, happy, and sustainable lives all across the world.

## Problem Statement
The project aims to analyze the data and answer some questions that are relative to  global development and poverty reduction for each dataset, and we will try to understand the problems that some countries are having then we will try to find the causation of it. 
in addition, we will use what I've learned in Machine learning to build a model that predict the happiness and well-being rate for some countries.

## Datasets and Inputs
This project uses the dataset of The World Development Indicators (WDI), which is the the World Bank's most comprehensive collection of cross-country development data. <br>

the source of the dataset: https://datatopics.worldbank.org/world-development-indicators/ <br>

here is the head of the dataset<br>

![image](https://user-images.githubusercontent.com/60386106/147043103-ef27def3-759c-4d93-a292-ef0c9d5b8693.png)
and the dataset of The Happy Planet Index which is a measure of sustainable wellbeing that ranks countries based on how effectively they use limited natural resources to produce long, happy lives.
<br>

you can find the dataset here: https://happyplanetindex.org/countries/ <br>

here is the head of the dataset<br>

![image](https://user-images.githubusercontent.com/60386106/147042973-8e668cea-c3d5-4821-aa06-5f6d9df555b0.png)



## Solution Statement
We will start with data cleaning and preparing, like checking the null values and so on, then we will choose some countries to focus on since the WDI dataset has so many countries
and we will choose which years we will be focusing on since not all the data are available
after that we will try to answer to interesting questions to better understands the datasets and the problems each country have
after that, we will build a model to predict the happiness and well-being rate for some countries and the reasons behind it.

## Benchmark Model
the project will run the data on multiple algorithms, the comparsion between them can be used to evaluate the performance.

## Evaluation Metrics

In this project, we aim to predict the HPI for some countries by the subject accurately, so since we have a basic regression problem, I’ll evaluate the models based on MSE, RMSE, MAE, MBE, Coefficient of determination (R²).
The mean of the absolute error between the actual and anticipated values in the dataset is the Mean absolute error. It calculates the average of the dataset’s residuals.
Mean Squared Error represents the difference between the original and forecasted values in the data set is the Mean Squared Error. It calculates the residuals’ variance.
The R-squared coefficient of determination shows the fraction of the variation in the dependent variable that the linear regression model can explain. It is a scale-free score, meaning that regardless matter how little or huge the values are, R square will be less than one.
So I think R-squared is the best metric that we should use in this problem because the question that we want to answer after training the models is: how close are we to predict the HPI that the countries will get in the future? and R-squared is suitable for this problem.

## Project Design
#### Collect & Explore the data
- Load Datasets and prepare training set and test set.
- understand the dataset, perform basic cleaning and processing, visualize the data to show the distribution of the datasets
- Determine how to calibrate the data.

#### Data Modeling & Training
- Features selection
- Determine Approaches to Model the datasets.
<br>  we will train the data with multiple supervise algorithms from sklearn such as logistic regression and SVM, and may try time series forecasting.
- select the best model based on the evaluation.


#### Test and Evaluate
Finally, use the Test data results to evaluate the performance of the output. The goal is to show a comparison of the models, and try to improve the best model to get the best result.

### Acknowledgements and References: <br>
Dataset resouces: <br>
WDI :  https://datatopics.worldbank.org/world-development-indicators/ <br>
HPI :  https://happyplanetindex.org/countries/ 


