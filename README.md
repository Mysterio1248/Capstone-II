# Capstone-II

# Stock Market Prediction: Analyzing Economic Data for Trends

## Project Overview

This project leverages a comprehensive dataset containing key economic and financial indicators for nine major economies, from the onset of the COVID-19 pandemic through early 2024. The goal is to predict stock market trends based on economic factors such as manufacturing, consumer sentiment, interest rates, inflation, unemployment, and GDP growth. Various machine learning models, including Random Forest, Decision Trees, SVM, and Gradient Boosting, have been implemented to evaluate and predict stock market performance.

## Objective

-> Predict stock market trends using macroeconomic and financial data.

-> Evaluate multiple machine learning algorithms to identify the most accurate model for predicting market movements.

-> Leverage Weka for data mining and model training, while implementing Python for data pre-processing and machine learning tasks.

## Dataset Description

The dataset provides insights into the economic health of nine major economies—Australia, Canada, China, Europe, Japan, New Zealand, Switzerland, the United Kingdom, and the United States. It includes features like:

- Manufacturing PMI: Economic health of manufacturing.

- Services PMI: Economic health of services.

- Consumer Confidence: Consumer sentiment and optimism.

- Interest Rates: Central bank's monetary policy.

- CPI YoY: Year-over-year inflation data.

- Core CPI: Inflation excluding volatile items.

- Unemployment Rate: Labor market health.

- GDP YoY: Economic output growth.

- Stock Prices: Open, High, Low, and Close prices of respective assets.

## Models Used

-> Random Forest

-> Decision Trees (J48)

-> Support Vector Machines (SVM)

-> Gradient Boosting

-> Neural Networks (MLP)

## Tools & Technologies

-> Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

-> Weka for data mining and model evaluation

-> Git and GitHub for version control

## Installation & Usage

- Install Weka:

Download and install Weka from the official site: [Download Weka here](https://www.cs.waikato.ac.nz/ml/weka/downloading.html).

After installing, you can use Weka's GUI or command-line interface for model training and evaluation.

- Run the Jupyter Notebook:

Open the Capstone-II.ipynb Jupyter notebook to train models and visualize predictions.

You can use the provided .arff or .csv files to import data and evaluate the model for the Weka part.

## Weka Instructions:

- After setting up Weka, open the software and load the dataset in .arff format (convert CSV to ARFF if needed).

- Select the classification or regression models (e.g., J48, RandomForest) and run the analysis.(based on your project requirements/goals)

- You can also use Weka’s built-in feature selection and data preprocessing tools as per your needs.

- Clone the repository to your local machine.

- Install dependencies:
```pip install -r requirements.txt```

- Run the Jupyter Notebook or Weka to train models and visualize predictions.

## Results
- The project compares the performance of various models and provides insights into which algorithms can best predict stock market trends based on economic data. 

- Evaluation metrics such as MAE, MSE, and R-squared assess the model's performance.

## Contributing
Feel free to fork the repository, create an issue, or submit a pull request. Contributions are welcome!
