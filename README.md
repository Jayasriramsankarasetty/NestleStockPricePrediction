# 📈 Stock Price Prediction using Linear Regression

Predicting stock prices is one of the most popular and challenging problems in the field of data science. In this project, we use historical stock data of **Nestlé India** to build a **Linear Regression model** that predicts the **Close Price** based on multiple trading indicators.

---

## 🚀 Project Overview

- **Goal**: Predict the future close price of the stock using machine learning.
- **Model Used**: Linear Regression
- **Dataset**: Historical stock data (`nestle.csv`)
- **Tech Stack**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 📂 Dataset Description

| Column Name             | Description                              |
|------------------------|------------------------------------------|
| Date                   | Date of the record                       |
| Open Price             | Opening price of the stock               |
| High Price             | Highest price of the day                 |
| Low Price              | Lowest price of the day                  |
| Close Price            | Closing price of the stock               |
| WAP                    | Weighted Average Price                   |
| No. of Trades          | Total number of trades on that day       |
| Turnover (Lacs)        | Total turnover in lakhs                  |
| Spread High-Low        | Difference between high and low prices   |
| Spread Close-Open      | Difference between close and open prices |
| Total Traded Quantity  | Number of shares traded                  |

---

## 📊 Exploratory Data Analysis

We analyzed:

- Correlation between features
- Price trends over time
- Patterns in trade volume by year, month, weekday
- Outliers using boxplots

---

## 🧠 Machine Learning Pipeline

1. **Preprocessing**
   - Cleaned missing values
   - Extracted `Year`, `Month`, `DayOfWeek` from `Date`

2. **Feature Selection**
   - Input features: Open Price, High Price, Low Price, WAP, Spread High-Low, Total Traded Quantity
   - Target: Close Price

3. **Modeling**
   - Train-Test Split (80/20)
   - Linear Regression from `scikit-learn`

4. **Evaluation Metrics**
   - R² Score
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)

5. **Visualization**
   - Actual vs Predicted Close Prices

---

## 📈 Results

| Metric     | Value          |
|------------|----------------|
| R² Score   | *[add your value]* |
| MAE        | *[add your value]* |
| RMSE       | *[add your value]* |

> The model performs reasonably well and can serve as a baseline for future improvements using more advanced models like XGBoost or LSTM.

---

## ✅ Key Learnings

- Hands-on experience with real-world stock data
- Feature engineering from time-series
- Applying linear regression to regression problems
- Evaluating model performance using common metrics

---

## 💡 Future Work

- Incorporate technical indicators (RSI, MACD, Moving Averages)
- Try ensemble models like Random Forest or XGBoost
- Explore deep learning (LSTM for sequential modeling)
- Deploy model as a Flask API or Streamlit app

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Yahoo Finance / NSE / BSE for stock data](https://www.nseindia.com/)

---

## 🙋‍♂️ Author

**Jayasriram Sankarasetty**  
📧 [jayasriramnani9@gmail.com](mailto:jayasriramnani9@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/jaysrirams) | [GitHub](https://github.com/Jayasriramsankarasetty)

---

## ⭐️ Show Your Support

If you found this project useful or insightful, please consider giving it a ⭐️ on GitHub!

