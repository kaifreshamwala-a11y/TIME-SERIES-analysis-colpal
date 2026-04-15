
Stock Market Analysis & Prediction (Assignment 1)

(1) Problem Statement
Financial markets are highly volatile and unpredictable. Analyzing historical stock data and predicting future trends is essential for investors to make informed decisions and minimize financial risks.

(2) Objective
To analyze historical stock price data of a specific company (e.g., RELIANCE or NSE Index).

To visualize trends using Moving Averages (50-day and 200-day).

To build a predictive model using Linear Regression to forecast future closing prices.

(3) Dataset
Source: Manually extracted/Downloaded from National Stock Exchange (NSE) India or Yahoo Finance.

Features: Date, Open, High, Low, Close, Adj Close, and Volume.

Size: Historical data for the past 1 year (2025-2026).

(4) Methodology
Data Preprocessing: Handled missing values, converted 'Date' column to datetime format, and sorted data chronologically.

EDA (Exploratory Data Analysis): Visualized the closing price history and calculated technical indicators like Moving Averages to identify trends.

Model Building: Implemented a Linear Regression model using 'Date' (converted to ordinal) or previous days' prices as features.

Evaluation: Split data into training and testing sets. Evaluated the model using Mean Squared Error (MSE) and R-squared (R2) score.

(5) Results
Trend Insight: The 50-day Moving Average crossover indicated a bullish/bearish trend during specific months.

Model Accuracy: The Linear Regression model achieved a high R-squared score, showing it could follow the general price direction effectively.

Visualization: Generated plots for Price vs. Time and Predicted vs. Actual prices.

(6) How to Run
Bash
# 1. Clone the repository
git clone https://github.com/kaifreshamwala-a11y/rollno_name_assignment1

# 2. Open the .ipynb file in Google Colab
# 3. Upload your stock dataset (e.g., stock_data.csv)
# 4. Run all cells to see the graphs and prediction results
(7) Conclusion
The project demonstrates that while stock prices are influenced by many factors, historical data analysis through Moving Averages and Linear Regression provides a foundational understanding of market direction. It highlights the importance of data visualization in financial analytics.

(8) AI Ethics & Responsible Usage Declaration
I used Google Gemini to assist in generating the Python code for data visualization and documentation structure.

Financial Risk: I acknowledge that this model is for academic purposes only and should not be used for actual financial trading or investment advice.

Data Privacy: Used publicly available historical stock data with no sensitive personal information.

(9) Student's details
Name: RESHAMWALA MOHAMMED KAIF SAMEER

Roll No: 47

UIN: 221A007

YEAR: TE-AIDS (2025-26)
