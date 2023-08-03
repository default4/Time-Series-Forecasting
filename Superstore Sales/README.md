## Overview:
This project presents a novel approach to predict the sales of furniture using a multivariate time series analysis with LSTM (Long Short-Term Memory) neural networks. The input features considered for the model include sales, quantity, discount, and profit. Along with building and evaluating an LSTM model, the project also contains a comprehensive Exploratory Data Analysis (EDA) section that helps in understanding the underlying structure of the data.

## Components

## 1. Data Loading
The dataset is loaded from a given Excel file and filtered to focus on the furniture category.

## 2. Exploratory Data Analysis (EDA)
A comprehensive EDA was conducted, focusing on:
* Initial Data Exploration: Includes a general overview and missing values check.
* Univariate Analysis: Studies the distribution of sales and profit.
* Bivariate Analysis: Covers correlation matrix and scatter plots for feature relationships.
* Outlier Detection: Includes a box plot for outlier identification.

## 3. Data Preprocessing
Relevant columns are selected, and the data is resampled by month and normalized using MinMaxScaler.

## 4. Preparing Data for LSTM
Sequences of 3 months of data are created to predict the 4th month.

## 5. Building and Training LSTM Model
An LSTM model is built and trained using sales, quantity, discount, and profit as input features.

## 6. Making Predictions and Evaluating the Model
The LSTM model is used to make predictions, and results are visualized.

## Key Technologies
* Pandas: For data manipulation and analysis.
* Scikit-Learn: For data preprocessing and normalization.
* Keras: For building and training the LSTM model.
* Matplotlib and Seaborn: For visualizing the data.

## How to Run
1. Ensure that all required libraries are installed.
2. Load the dataset "Superstore.xls" containing sales data.
3. Run the code provided for EDA to explore the data.
4. Continue with preprocessing, training, and evaluation of the LSTM model.

## Conclusion
The project demonstrates a unique combination of LSTM modeling with EDA, allowing for a deep understanding of the time series data and a robust prediction of future sales. The insights from the EDA part guide the subsequent data preprocessing and modeling choices, resulting in a well-informed and comprehensive approach to time series forecasting.

