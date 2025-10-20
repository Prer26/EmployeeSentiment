# EmployeeSentiment

## 📘 Overview
This project analyzes employee messages to assess overall sentiment and engagement levels. It performs labeling, scoring, ranking, and predictive modeling on message data.

## 🧩 Features Implemented
1. **Sentiment Labeling** – Using VADER to classify each message as Positive, Negative, or Neutral.  
2. **Exploratory Data Analysis (EDA)** – Visualizing sentiment distribution and employee-level sentiment patterns.  
3. **Monthly Sentiment Scoring** – Calculating monthly cumulative sentiment per employee.  
4. **Employee Ranking** – Identifying top positive and negative employees.  
5. **Flight Risk Detection** – Detecting employees with ≥4 negative messages in a 30-day window.  
6. **Predictive Modeling** – A Linear Regression model predicts sentiment trends based on message length.

## 🧠 Methodology
- Used `VADER` sentiment analysis (`vaderSentiment`).
- Performed aggregations and visualizations using `pandas`, `matplotlib`, and `seaborn`.
- Built a linear regression model with `scikit-learn`.

## 📊 Key Insights
- Positive and Negative messages are well-separated by sentiment scores.
- Monthly sentiment variation highlights engagement fluctuations.
- Employees sending ≥4 negative messages are flagged as flight risks.
- Message length correlates weakly with sentiment intensity (as seen in regression model).

## ⚙️ Setup
```bash
pip install pandas numpy matplotlib seaborn scikit-learn vaderSentiment
