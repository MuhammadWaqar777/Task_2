# Task 2: Predict Future Stock Prices (Short-Term)

## ✅ Objective
Use historical stock data to predict the **next day's closing price** using **machine learning models**.

## ✅ Dataset
- **Source:** Yahoo Finance (via `yfinance` Python library)
- **Features Used:**
  - Open
  - High
  - Low
  - Volume
- **Target:**
  - Next day's Close price
## ✅ Steps Performed
1. Fetched historical stock data (Apple Inc. - AAPL) using `yfinance`.
2. Selected relevant features: Open, High, Low, Volume.
3. Created the target variable: Next day's Close price.
4. Split data into training (80%) and testing (20%) sets.
5. Trained a **Linear Regression model** to predict the next day's Close price.
6. Evaluated the model using **Mean Squared Error (MSE)**.
7. Plotted **Actual vs Predicted Closing Prices**.

# ✅ Tools & Libraries Used
- **Python**
- **pandas** (data handling)
- **yfinance** (data fetching)
- **scikit-learn** (machine learning)
- **matplotlib**, **seaborn** (visualization)

# ✅ Model Used
  - Features: `Open`, `High`, `Low`, `Volume`
  - Target: `Next day's Close`

## ✅ How to Run
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
