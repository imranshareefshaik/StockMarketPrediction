# StockMarketPrediction

# Stock Price Prediction of Reliance Industries Limited

## Business Objective
The main objective of this project is to predict the stock prices of **Reliance Industries Limited** for the next **30 days**. The project utilizes historical stock data from **2015 to 2022** to identify short-term and long-term trends, analyze the impact of external factors and significant events, and provide accurate forecasts for the upcoming month.

## Data Description
The project uses stock market data collected from **January 1, 2015, to February 28, 2023**.

### Attributes:
- **Date**: Date of trade
- **Open**: Opening price of the stock
- **High**: Highest price of the stock on that day
- **Low**: Lowest price of the stock on that day
- **Close**: Closing price of the stock
- **Adj Close**: Adjusted closing price (adjusted for splits, dividends, and capital gain distributions)
- **Volume**: Volume of stock traded on that day

### Data Source
You can download the dataset from a stock market data provider or use the **YFinance** library to fetch the data programmatically.

## Tools & Technologies
The project is developed using the following technologies:
- **Python** programming language
- Libraries:
  - `NumPy`, `Pandas` (Data Manipulation)
  - `Matplotlib`, `Seaborn` (Data Visualization)
  - `SciPy`, `scikit-learn` (Machine Learning Models)
  - `TensorFlow`, `Keras` (Deep Learning)
  - `Streamlit` (Deployment)
- Machine Learning Models Used:
  - **Support Vector Regression (SVR)**
  - **Random Forest**
  - **K-Nearest Neighbors (KNN)**
  - **Long Short-Term Memory (LSTM)**
  - **Gated Recurrent Units (GRU)**

## Installation
To run this project, install all the required dependencies using the following command:
```sh
pip install -r requirements.txt
```
Ensure you have **Python** installed before running the above command. You can download Python from [here](https://www.python.org/downloads/).

## Model Building
The project involves developing and evaluating multiple **machine learning models**, including **SVR, Random Forest, KNN, LSTM, and GRU**.
- The **LSTM model** demonstrated the **highest accuracy** and was chosen for deployment.

## Deployment
The project is deployed using **Streamlit**, enabling users to interact with the model and make **stock price predictions** based on historical data.

### Running the Project
To run the project locally, execute the following command in your terminal or command prompt:
```sh
streamlit run app.py
```

## Conclusion
This project integrates **data analysis, machine learning, and software development** to tackle the complex challenge of stock price prediction. It demonstrates how **historical data** and **advanced models** can be leveraged to make informed financial market predictions.

## Project Link
[Access the Deployed Project](#) (Replace with actual deployment link)

