# Internship-work-Primetrade.ai

# 📊 Trader Behavior & Market Sentiment Analysis

This project is part of the hiring assignment for the **Junior Data Scientist** role at **PrimeTrade.ai**. The goal of this analysis is to uncover insights into how trader behavior correlates with market sentiment (Fear/Greed) using real historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

---

## 🚀 Objective

To analyze trader performance and behavior in relation to market sentiment by:
- Merging two datasets: trader execution data and sentiment index
- Cleaning and preprocessing data
- Exploring trends in trade size, PnL, and position across different sentiment phases
- Providing actionable insights that can influence trading strategy

---

## 📁 Dataset Overview

### 1. 🧾 Market Sentiment Data (Fear & Greed Index)
- **Columns**: `date`, `classification`
- Classification levels: `Extreme Fear`, `Fear`, `Neutral`, `Greed`, `Extreme Greed`

### 2. 📈 Trader Execution Data (from Hyperliquid)
- **Columns include**:
  - `Account`, `Symbol`, `Execution Price`, `Size`, `Side`, `Time`, `Start Position`, `Event`, `Closed PnL`, `Size USD`, etc.

---

## 🧼 Preprocessing Steps

- Converted timestamps to datetime format
- Cleaned and standardized column names
- Merged datasets based on matching `date`
- Filtered necessary columns for analysis

---

## 🔍 Exploratory Data Analysis (EDA)

- ✅ **Average Closed PnL by Sentiment**
- ✅ **Total Trades Executed by Sentiment**
- ✅ **Average Trade Size (USD) by Sentiment**
- ✅ **Average Starting Position by Sentiment**
- ✅ Visualized trends using bar plots and histograms

---

## 📊 Key Insights

- **Higher average trade sizes** observed during `Greed` and `Extreme Greed`, suggesting higher trader confidence.
- **PNL tends to be higher** during neutral or positive sentiment phases.
- **Lower trade activity and size** noted during `Fear` and `Extreme Fear`, showing market hesitation.
- **Trade behavior** shifts clearly with market sentiment, which can guide risk-adjusted strategy development.

---

## 🛠️ Tech Stack

- Python (Pandas, Matplotlib, Seaborn)
- Google Colab / Jupyter Notebook
- Git & GitHub for version control

---

## 📁 File Structure

📊 Trader_Sentiment_Analysis.ipynb → Main analysis notebook
┗ README.md → Project overview and insights


---

## 📬 Submission

This notebook has been submitted as part of the assignment for:
> **Junior Data Scientist – Trader Behavior Insights**  
> PrimeTrade.ai / Bajarangs

---

## 👤 Author

**Aman Kumar**  
Final Year B.Tech Student | Data Science & Machine Learning Enthusiast  
[GitHub](https://github.com/Amankar003)

---

## 📌 Note

This assignment demonstrates practical skills in:
- Data cleaning and merging
- EDA and visualization
- Behavioral analysis based on sentiment
- Insight generation for strategic decisions

---

