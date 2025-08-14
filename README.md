# OutriX_tasks – Task 1

This repository contains **Task 1: Stock Price Trend Analysis** for my Finance Analytics Internship with OutriX.

**What I Did:**
- Fetched Apple's historical stock data using Python and yfinance.
- Calculated daily returns, moving averages (20-day & 50-day), and rolling volatility.
- Created visualizations (stock price trends, daily return histogram, volatility chart) using Matplotlib and Seaborn.

**Key Insight:**  
The moving averages show long-term trends, and volatility spikes highlight periods of higher risk.

## Task 2: Portfolio Risk & Return Analysis

In this task, I analyzed the risk and return of a portfolio consisting of multiple stocks (e.g., AAPL, MSFT, GOOGL, AMZN) using Python.

### Key Components:
- Downloaded historical stock price data using `yfinance`.
- Calculated **daily returns**, **expected annual return**, **portfolio volatility**, and **Sharpe ratio**.
- Used `NumPy` and `Pandas` for calculations and data processing.
- Visualized:
  - **Cumulative returns** to show portfolio growth.
  - **Correlation heatmap** to assess diversification.
- Provided performance insights based on risk-return metrics.

> Tools Used: Python, Jupyter Notebook, yfinance, NumPy, Pandas, Matplotlib, Seaborn

## Task 5: Loan Default Prediction

This task involved building a **machine learning model** to predict whether a loan applicant is likely to default, using historical loan data.

### Steps Performed:
- **Data Loading & Cleaning**: Imported `loan_data.csv`, removed missing values, and stripped column names.
- **Exploratory Analysis**: Visualized loan default distribution.
- **Data Preprocessing**:
  - Encoded categorical variables using one-hot encoding.
  - Scaled numerical features using StandardScaler.
- **Model Building**: Trained a **Logistic Regression** model.
- **Evaluation**:
  - Calculated **accuracy**, **confusion matrix**, and **classification report**.
  - Plotted **feature importance** to identify key predictors of loan default.
  
### Key Insights:
- Credit history and loan amount were significant predictors.
- Logistic Regression effectively classified borrowers based on default risk.
- The model achieved an accuracy of approximately **XX%**.

> **Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
