# 🏪 Rossmann Store Sales Analytics & Forecasting

> An end-to-end Data Science project that combines **Python**, **SQL**, **Machine Learning**, and **Power BI** to analyze historical Rossmann store sales and build an interactive business intelligence dashboard.

---

## 📌 Project Overview

Retail businesses generate massive amounts of sales data every day. Understanding this data can help managers optimize promotions, inventory, staffing, and overall business strategy.

This project analyzes the **Rossmann Store Sales Dataset** by performing:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- SQL Business Analysis
- Feature Engineering
- Machine Learning Sales Forecasting
- Interactive Power BI Dashboard Development

---

# 📊 Dashboard Pages

## 📈 Executive Overview

Provides a high-level summary of business performance.

### Features

- Total Revenue
- Average Sales
- Total Customers
- Total Stores
- Average Customers
- Monthly Revenue Trend

---

## 🏬 Store Performance

Analyzes store-level performance.

### Features

- Top 10 Stores by Revenue
- Revenue by Store Type
- Revenue by Assortment

---

## 👥 Customer & Promotion Analysis

Analyzes customer behavior and promotion effectiveness.

### Features

- Promotion vs No Promotion
- Average Sales by State Holiday
- Monthly Customer Trend
- Sales vs Customers Relationship

---

## 🤖 Machine Learning & Forecasting

Compares forecasting models and evaluates prediction quality.

### Features

- Best Performing Model
- R² Score Comparison
- Actual vs Predicted Sales
- Feature Importance
- Residual Analysis

---

# 🛠️ Tech Stack

| Category | Tools |
|-----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Power BI |
| Machine Learning | Scikit-Learn, XGBoost |
| Database | SQL |
| Notebook | Jupyter Notebook |

---

# 📂 Project Structure

```
Rossmann-Store-Sales-Analytics/
│
├── data/
│   ├── raw/
│   │   ├── train.csv
│   │   └── store.csv
│   │
│   └── processed/
│       └── cleaned_sales.csv
│
├── notebooks/
│   └── Rossmann_Sales_Forecasting.ipynb
│
├── sql/
│   └── business_analysis.sql
│
├── powerbi/
│   └── Rossmann_Dashboard.pbix
│
├── images/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   ├── dashboard_page3.png
│   ├── dashboard_page4.png
│   ├── feature_importance.png
│   ├── actual_vs_predicted.png
│   └── residual_distribution.png
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Machine Learning Models

The following regression models were trained and evaluated.

| Model | R² Score | RMSE | MAE |
|--------|---------:|------:|------:|
| Linear Regression | 0.5963 | 2455.39 | 1702.65 |
| Decision Tree | 0.8818 | 1328.51 | 819.84 |
| XGBoost | 0.9018 | 1210.80 | 815.29 |
| ⭐ Random Forest | **0.9067** | **1180.31** | **733.50** |

---

# 📈 Dashboard Preview

## Executive Overview

> *(Insert Dashboard Screenshot Here)*

---

## Store Performance

> *(Insert Dashboard Screenshot Here)*

---

## Customer & Promotion Analysis

> *(Insert Dashboard Screenshot Here)*

---

## Machine Learning Dashboard

> *(Insert Dashboard Screenshot Here)*

---

# 🔍 Feature Engineering

Several new features were engineered to improve model performance.

Examples include:

- Competition Duration
- Promo Duration
- Is Weekend
- Month
- Week of Year
- Competition Availability
- Holiday Encoding
- Store Type Encoding
- Assortment Encoding

---

# 📊 Exploratory Data Analysis

The dataset was analyzed to understand:

- Sales Distribution
- Customer Trends
- Promotion Effectiveness
- Holiday Impact
- Store Type Performance
- Correlation Between Sales and Customers

---

# 💡 Key Business Insights

### 📌 Revenue

- Total Revenue exceeded **₹5.87 Billion**.
- Store Type **A** generated the highest revenue.

---

### 📌 Promotions

Stores running promotional campaigns generated significantly higher average sales compared to non-promotional days.

---

### 📌 Customers

Sales showed a strong positive relationship with customer footfall, indicating customer traffic is a primary revenue driver.

---

### 📌 Assortment

Assortment Types **A** and **C** contributed almost the entire revenue share.

---

### 📌 Machine Learning

Among all regression models, **Random Forest** achieved the highest forecasting accuracy with:

- R² = **0.9067**
- RMSE = **1180.31**
- MAE = **733.50**

making it the best-performing model for future sales prediction.

---

# 🚀 How to Run

## Clone Repository

```bash
git clone https://github.com/yourusername/Rossmann-Store-Sales-Analytics.git
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run Notebook

```bash
jupyter notebook
```

---

## Open Dashboard

Open the following file using **Microsoft Power BI Desktop**

```
powerbi/Rossmann_Dashboard.pbix
```

---

# 📌 Dataset

Rossmann Store Sales Dataset

Contains:

- Daily Sales
- Customers
- Promotions
- Holidays
- Store Information
- Competition Details

---

# 📚 Skills Demonstrated

✔ Data Cleaning

✔ Feature Engineering

✔ SQL Analysis

✔ Data Visualization

✔ Business Intelligence

✔ Machine Learning

✔ Model Evaluation

✔ Power BI Dashboard Development

✔ Business Storytelling

---

# 📷 Future Improvements

- Deploy forecasting model using Streamlit
- Build real-time sales prediction API
- Add interactive forecasting in Power BI
- Incorporate time-series forecasting models (Prophet/LSTM)

---

# 👨‍💻 Author

**Utsav Thakur**

B.Sc. Data Science | DIT University

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

# ⭐ If you found this project useful, consider giving it a star!
