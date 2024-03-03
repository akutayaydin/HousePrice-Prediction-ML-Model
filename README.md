# NYC Real Estate Price Prediction Model

This repository contains a machine learning model for predicting real estate prices in New York City. The model utilizes various features such as property characteristics, location, and sale date to predict the sale price of properties.

## Dataset

The dataset used for training and testing the model is the NYC Rolling Sales dataset. It contains information about real estate sales in New York City, including details about the properties, such as total units, square footage, neighborhood, and more.

You can obtain the dataset from the following link: [NYC Rolling Sales Dataset](https://raw.githubusercontent.com/akutayaydin/Magnimind-1/main/nyc-rolling-sales.csv)

## Model Development

The model development process involves several steps:

1. Data Preprocessing: Handling missing values, transforming categorical variables, and scaling numerical features.
2. Model Selection: Testing different regression models, including Linear Regression, Random Forest, XGBoost, Lasso, and Ridge Regression.
3. Model Evaluation: Evaluating model performance using metrics such as Root Mean Squared Error (RMSE) and R-squared.

## Usage

To use the model, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Load the dataset into your environment.
4. Train the model using the provided Jupyter notebook or Python script.
5. Test the trained model on new data to make predictions.

## Results

The model achieved a certain level of accuracy in predicting real estate prices based on the given features. Different models were tested and evaluated, with some models performing better than others depending on the dataset characteristics.

## Acknowledgments

The dataset used in this project is sourced from the NYC Rolling Sales dataset, which is publicly available.
