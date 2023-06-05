# Predicting Customer Ratings for Amazon Electronic Products

## About

This repository contains code and resources for a project I worked on to predict ratings customers would give to Amazon's electronic products based on the summaries and reviews that they left. In this project, I used natural language processing to extract meaningful data from customer reviews and supervised machine learning techniques to build models that learn from the resultant data to classify a product as receiving a 1, 2, 4, or 5 star rating.

The goal of this project is to develop a predictive model that can accurately identify ratings for products based on the summary and review left by customers. This repository includes data cleaning, exploratory data analysis, feature selection and engineering, model selection and hyperparameter tuning, and evaluation of the model's performance on a held-out test set.

To learn more about the problem description, data description, and steps, open the `PredictRating.ipynb` file.

## How to Run

- Clone this repository
- Install Python
- Download the `5-core` dataset in the `Electronics` category in the `"Small" subsets for experimentation dataset` section  <a href = "https://nijianmo.github.io/amazon/index.html?fbclid=IwAR0_5K7tu7q-ROrBlvDceA1KFPrasHFZWx7X-IfeTgG2ZQ9WcA11pH8JEjo#subsets" target="_blank">here</a> and place it in the same directory as the `PredictRating.ipynb` file
- run the command `pip install -r requirements.txt` to install any dependencies
- open the notebook locally by running the command `jupyter notebook PredictRating.ipynb` and run all the cells

