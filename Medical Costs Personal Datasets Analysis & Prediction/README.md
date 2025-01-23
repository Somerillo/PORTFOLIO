# Analyzing Medical Insurance Costs

![alt text](<pngimg.com - under_construction_PNG46.png>)

## Overview
In this project we analyze the features correlations from “Medical Cost Personal Datasets”. First, we study the distributions and correlations to propose a new categorical variable associated with health risk. 
Focusing on the target variable ‘price’ we find the baseline model from health insurance companies to apply charges.
Finally, we cluster visually the dataset and obtain predictive models.

## Motivation
To pass the second hackathon.

## Features
Data Preprocessing: We employ pairplots, correlation matrix heatmap, feature engineering, data scaling, log transformation and anti-transformation, outliers removal by residues method.
Modeling: Implementation of linear regression, and KMeans clustering.
Evaluation: The evaluation metrics are R^2 and residues.
Visualization: Pairplots, heatmap, scatter plots, histogram, regression curve with error band, interactive USA regions map.

## Installation
!pip install pandas numpy scikit-learn matplotlib seaborn plotly psycopg2-binary sqlalchemy