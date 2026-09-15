# OIBSIP

# 🚀 Oasis Infobyte Internship (OIBSIP) — Data Analytics Projects

Welcome to my official repository for the **Oasis Infobyte Virtual Internship Program (OIBSIP)** under the **Data Analytics** track. This repository contains two complete end-to-end data analytics and financial modeling projects built using Python in Jupyter Notebook.

---

# 🥤 Project 1: Financial Statement Analysis & DCF Valuation of The Coca-Cola Company

## 1. Project Objective & Scope
The primary objective of this project is to conduct an in-depth, multi-year financial performance evaluation of **The Coca-Cola Company** spanning FY 2009 through FY 2018. By leveraging corporate financial statements, the project integrates advanced financial ratio analysis, 3-factor DuPont Return on Equity (ROE) decomposition, and a Discounted Cash Flow (DCF) model to determine the intrinsic equity value of the firm.

---

## 2. Technical Stack & Dependencies
* **Language:** Python 3.x
* **Core Data Libraries:** `pandas`, `numpy`
* **Visualization Engine:** `matplotlib`, `seaborn`
* **Development Environment:** Jupyter Notebook

---

## 3. Analytical Framework & Workflow

### 3.1 Financial Statement Cleaning & Preprocessing
* **Data Structuring:** Standardized historical Balance Sheets, Income Statements, and Cash Flow Statements across a 10-year timeline.
* **Data Integrity:** Addressed missing values, reconciled accounting line items, and verified cross-statement coherence across reporting periods.

### 3.2 DuPont ROE Decomposition Analysis
Deconstructed overall profitability using the classic 3-Factor DuPont equation:

$$\text{ROE} = \text{Net Profit Margin} \times \text{Asset Turnover} \times \text{Equity Multiplier}$$

* **Net Profit Margin ($\text{Net Income} / \text{Revenue}$):** Evaluated operational efficiency, cost management, and pricing power.
* **Asset Turnover ($\text{Revenue} / \text{Total Assets}$):** Measured how effectively the company utilizes its total asset base to generate top-line revenue.
* **Equity Multiplier ($\text{Total Assets} / \text{Total Equity}$):** Analyzed financial leverage, capital structure decisions, and long-term solvency risk.

### 3.3 Discounted Cash Flow (DCF) Modeling
* **FCFF Forecasting:** Calculated and projected Free Cash Flow to Firm (FCFF) using historical operating cash flows and capital expenditures.
* **WACC & Terminal Value:** Derived the Weighted Average Cost of Capital (WACC) and applied perpetual growth assumptions to estimate intrinsic enterprise value and per-share equity valuation.

---
---

# 📱 Project 2: Google Play Store Ecosystem Analysis & Sentiment Mining

## 1. Project Objective & Scope
This project delivers a comprehensive Exploratory Data Analysis (EDA) on the **Google Play Store** mobile market ecosystem. The goal is to uncover market density trends, evaluate freemium vs. paid pricing strategies, model category revenue distributions, and mine qualitative user feedback using Natural Language Processing (NLP).

---

## 2. Technical Stack & Dependencies
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Static & Interactive Visualization:** `matplotlib`, `seaborn`, `plotly.express`
* **Natural Language Processing (NLP):** `nltk` (`SentimentIntensityAnalyzer` / VADER)
* **Development Environment:** Jupyter Notebook

---

## 3. Analytical Framework & Workflow

### 3.1 Data Sanitation & Anomaly Removal
* **Type Conversion:** Cleaned messy string metrics (`Installs`, `Price`, `Size`) into numerical data types (`int`, `float`, and standardized Megabytes `MB`).
* **Anomaly Handling:** Filtered out erroneous ratings ($>5.0$) caused by misaligned dataset rows (e.g., Kaggle Row 10472).
* **Deduplication:** Dropped duplicate app records based on unique application identifiers to eliminate aggregation bias.

### 3.2 Market Saturation & Revenue Modeling
* **Category Distribution:** Mapped app density across categories, highlighting heavy market saturation in **Family**, **Game**, and **Tools**.
* **Monetization Breakdown:** Evaluated Free vs. Paid models—over **92%** of applications adopt a free download strategy, with freemium and in-app purchase mechanics generating the majority of industry revenue.

### 3.3 VADER NLP Sentiment Analysis
* **Sentiment Classification:** Processed thousands of user reviews through NLTK's VADER model to categorize feedback into **Positive**, **Neutral**, and **Negative** sentiment scores.
* **Category Satisfaction Mapping:** Computed category-level positive sentiment ratios, identifying **Health & Fitness** and **Personalization** as leading sectors in user satisfaction.

### 3.4 Interactive Visualizations
* **Plotly Bubble Chart:** Built an interactive scatter visual mapping total app volume against average user ratings, with bubble dimensions scaled dynamically to download volumes.

---

## 💡 Key Summary Takeaways

1. **Coca-Cola Performance:** Profitability stability is primarily anchored by strong Net Profit Margins, offsetting capital intensity and moderate asset turnover rates.
2. **App Store Strategy:** Upfront paid models face steep user adoption resistance; developers should prioritize freemium monetization strategies.
3. **Payload Impact:** Application size (MB) exhibits negligible negative correlation with total installs, proving functional user experience outweighs file size concerns.

---


# 📱 Project 2: Google Play Store Ecosystem Analysis & Sentiment Mining

## 1. Project Objective & Scope
This project delivers a comprehensive Exploratory Data Analysis (EDA) on the **Google Play Store** mobile market ecosystem. The goal is to uncover market density trends, evaluate freemium vs. paid pricing strategies, model category revenue distributions, and mine qualitative user feedback using Natural Language Processing (NLP).

---

## 2. Technical Stack & Dependencies
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Static & Interactive Visualization:** `matplotlib`, `seaborn`, `plotly.express`
* **Natural Language Processing (NLP):** `nltk` (`SentimentIntensityAnalyzer` / VADER)
* **Development Environment:** Jupyter Notebook

---

## 3. Analytical Framework & Workflow

### 3.1 Data Sanitation & Anomaly Removal
* **Type Conversion:** Cleaned messy string metrics (`Installs`, `Price`, `Size`) into numerical data types (`int`, `float`, and standardized Megabytes `MB`).
* **Anomaly Handling:** Filtered out erroneous ratings ($>5.0$) caused by misaligned dataset rows (e.g., Kaggle Row 10472).
* **Deduplication:** Dropped duplicate app records based on unique application identifiers to eliminate aggregation bias.

### 3.2 Market Saturation & Revenue Modeling
* **Category Distribution:** Mapped app density across categories, highlighting heavy market saturation in **Family**, **Game**, and **Tools**.
* **Monetization Breakdown:** Evaluated Free vs. Paid models—over **92%** of applications adopt a free download strategy, with freemium and in-app purchase mechanics generating the majority of industry revenue.

### 3.3 VADER NLP Sentiment Analysis
* **Sentiment Classification:** Processed thousands of user reviews through NLTK's VADER model to categorize feedback into **Positive**, **Neutral**, and **Negative** sentiment scores.
* **Category Satisfaction Mapping:** Computed category-level positive sentiment ratios, identifying **Health & Fitness** and **Personalization** as leading sectors in user satisfaction.

### 3.4 Interactive Visualizations
* **Plotly Bubble Chart:** Built an interactive scatter visual mapping total app volume against average user ratings, with bubble dimensions scaled dynamically to download volumes.

---

## 💡 Key Summary Takeaways

1. **Coca-Cola Performance:** Profitability stability is primarily anchored by strong Net Profit Margins, offsetting capital intensity and moderate asset turnover rates.
2. **App Store Strategy:** Upfront paid models face steep user adoption resistance; developers should prioritize freemium monetization strategies.
3. **Payload Impact:** Application size (MB) exhibits negligible negative correlation with total installs, proving functional user experience outweighs file size concerns.

```text
OIBSIP/
├── FinancialAnalytics-L1-Task3-(Data_Cleaing)CocaColaValuation/
│   ├── CocaCola_Valuation_Analysis.ipynb
    ├── CocaCola_financial_dashboard.ipynb
│   └── cocacola_financials.xlsx
│   
│
└── DataAnalytics-L2-Task4-PlayStoreEDA/
|    ├── Google_Play_Store_EDA.ipynb
|    ├── apps.csv
|    └── user_reviews.csv
└── README.md

