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

In this project, we aim to predict the HPI for some countries by the subject accurately, so misclassification rate is chosen as the assessment measure to compare the performance of different models. So, to decide what is the best algorithm to use for this problem, we need to measure the accuracy, precision and recall of the models.

## Project Design
#### Collect & Explore the data
- Load Datasets and prepare training set and test set.
- understand the dataset, perform basic cleaning and processing, visualize the data to show the distribution of the datasets
- Determine how to calibrate the data.

#### Extract Features
Devise new features based on the given features, some intuitions.
Create a generator to break the data to be trained into batches.
Determine Approaches to Modeling the Problem
divide the data into second segments and then generate features that were based on the readings.
Train and Classify with benchmark
Work will be done to classify the activities using a classifier from sklearn such as logistic regression as a benchmark and fine tune the model's hyperparameters.
Split the data into Training and Test sets.
Improve the classification with an ANN
The solution then proposes a Artificial neural network designed to take a 10. design a classifier that will be used for the Artificial Neural Network (ANN).
#### Data Modeling


#### Test and Evaluate
Finally, use the Test data results to evaluate the performance of the classifier output. The goal is to show a comparison with the traditional classification models to an ANN, and understanding any improvements in terms of computational costs while maintaining similar accuracy.

### Acknowledgements and References: <br>



