## House Price Prediction Model
This repository contains the code for a financial predictive model developed as part of a capstone project at Freddie Mac. The model forecasts Arizona's House Price Index using neural network and time series modeling techniques, achieving 72% accuracy.

Overview
The script performs the following main tasks:

Data Preprocessing and Exploration

Loads multiple datasets related to Arizona's housing market.
Merges datasets to create a comprehensive view of housing price indices and relevant economic indicators.
Analyzes economic factors such as CPI, GDP, and mortgage rates.
Purchase Behavior Analysis

Calculates average housing affordability.
Highlights that 92.9% of homes in the Sierra Vista-Douglas MSA are affordable to median-income families.
Model Implementation

Utilizes LSTM neural networks for time series prediction.
Implements data preprocessing techniques like scaling and imputing missing values.
Model Training and Evaluation

Splits data into training and testing sets.
Trains the LSTM model on the dataset.
Uses early stopping to prevent overfitting.
Prediction Generation

Provides a function to generate housing price predictions for various regions.
Requirements
Python 3.7+
pandas
numpy
scikit-learn
tensorflow
Usage
Ensure all required libraries are installed.
Place the dataset Excel file in the same directory as the script.
Run the script in a Python environment.
Data
The script uses an Excel file containing data on CPI, GDP, mortgage rates, and housing prices.

Output
The script outputs:

Analysis of economic indicators and housing market trends.
Model performance metrics.
Sample housing price predictions for various regions.
Note
This script is for educational and demonstration purposes. The effectiveness of the predictions should be validated in a real-world scenario before implementation.
