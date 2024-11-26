# Capstone-II

# Analyzing Macroeconomic Data for Predicting Future Economic Trends Using WEKA

## Project Overview

This project utilizes a comprehensive dataset containing key macroeconomic indicators from multiple economies to predict future economic trends. The dataset spans from the onset of the COVID-19 pandemic to early 2024 and includes various economic factors such as GDP growth, unemployment rates, consumer sentiment, inflation, interest rates, and stock market data. We employ WEKA, a popular data mining tool, to apply various machine learning models and extract valuable insights from this data.

The goal of this project is to demonstrate how macroeconomic data can be analyzed to predict future economic outcomes using machine learning techniques..

## Objective

-> Predict future economic trends using macroeconomic indicators.

-> Evaluate machine learning algorithms to determine the most accurate models for forecasting economic trends.

-> Leverage WEKA for the data mining process, including model training and evaluation

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

## Note: 

- While stock prices (Close) are used as a target variable in our project models, this approach can be generalized to predict various other economic outcomes, including consumer confidence or unemployment rates, depending on the focus of the analysis.

## Models Used

-> Random Forest

-> Decision Trees (J48)

-> Support Vector Machines (SVM)

-> Linear Regression

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
- The project uses macroeconomic data to evaluate multiple models and predict future economic trends. We assess the performance of different machine learning algorithms based on metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared. 

- Evaluation metrics such as MAE, MSE, and R-squared assess the model's performance.

## Contributing
Feel free to fork the repository, create an issue, or submit a pull request. Contributions are welcome!
