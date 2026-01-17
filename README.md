Airbnb Data Analysis and Price Prediction
Project Overview

This project focuses on exploratory data analysis (EDA) and machine learning modeling using an Airbnb listings dataset. The objective is to analyze key factors influencing Airbnb listing prices and to build a predictive model that can classify or estimate pricing behavior based on location, reviews, and other listing attributes.

The project demonstrates practical skills in data preprocessing, visualization, feature analysis, and supervised learning, making it suitable for data science and analytics portfolios.

Dataset

Source: Airbnb Listings Dataset (CSV format)

File used: datasets.csv

Key Features:

price

latitude

longitude

neighbourhood_group

number_of_reviews

Additional listing-related attributes

Technologies Used

Programming Language: Python

Libraries & Tools:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Environment: Jupyter Notebook

Project Workflow
1. Data Loading & Inspection

Loaded the dataset using Pandas

Checked shape, structure, and basic statistics

Identified missing and inconsistent values

2. Exploratory Data Analysis (EDA)

Visualized geographical distribution using latitude and longitude

Analyzed price trends across neighbourhood groups

Studied the relationship between:

Price and number of reviews

Price and location

Used bar plots and scatter plots for insight generation

3. Data Preprocessing

Handled missing values

Selected relevant features

Prepared data for machine learning

Split dataset into training and testing sets

4. Machine Learning Model

Implemented a Random Forest Classifier

Trained the model on processed data

Evaluated performance using classification metrics

5. Model Evaluation

Generated a classification report

Assessed precision, recall, and overall performance

Results & Insights

Location (neighbourhood group, latitude, longitude) has a strong influence on pricing

Listings with higher engagement (reviews) show distinct pricing patterns

Random Forest performed effectively for classification tasks on the dataset
