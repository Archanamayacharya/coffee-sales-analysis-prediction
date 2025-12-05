# coffee-sales-analysis-prediction
Exploratory analysis and machine learning to understand and predict coffee sales trends

# Coffee Sales Analysis & Prediction

## 📌 Overview
This project analyzes coffee shop sales data to understand customer purchasing behavior, product popularity, payment preferences, and time-based sales trends. Feature engineering and machine learning models were applied to identify key revenue drivers and predict sales.

📊 Dataset Size: 1,133 transactions  
📅 Time Period: March 2024 – July 2024  
👩‍💻 Author: Archana Anil Mayacharya

---

## ✅ Problem Statement
Analyze coffee sales data to:
- Understand customer and product preferences
- Identify high-performing coffee products
- Analyze daily, weekly, and seasonal sales trends
- Predict sales using machine learning models

---

## 🛠 Tools & Technologies
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  
- Statsmodels  
- Power BI  

---

## 🔄 Project Workflow
### 1. Data Cleaning
- Combined date and time into a proper timestamp
- Removed invalid timestamps and duplicates
- Standardized categorical values
- Cleaned monetary values
- Handled missing values for cash transactions

### 2. Feature Engineering
- Extracted date features (month, day, weekday, weekend)
- Encoded payment type (cash/card) and coffee types
- Built customer behavior features:
  - Transaction count
  - Total spent
  - Average spent
- Created coffee-level metrics:
  - Coffee popularity
  - Coffee revenue
- Added pricing indicator (above average price)

### 3. Exploratory Data Analysis (EDA)
- Payment method distribution
- Coffee popularity and revenue contribution
- Daily sales trends
- Sales by day of week
- Weekend vs weekday comparisons
- Correlation analysis of numeric features

### 4. Machine Learning
- Task: Predict sales amount (money)
- Train-test split: 80/20

**Models Used:**
- Linear Regression (baseline)
- Random Forest Regressor

---

## 📈 Model Performance
| Model | RMSE | R² Score |
|------|-----|----------|
| Linear Regression | 1.74 | 0.87 |
| Random Forest | 1.21 | 0.94 |

🔹 Random Forest explained ~94% of the variance in sales.

---

## 🔍 Key Insights
- Card payments account for ~93% of transactions
- Latte is the most popular and highest-revenue product
- Sales peak on Tuesdays and weekends
- Customer average spending is the strongest revenue driver
- Product popularity matters more than payment type or weekend effect

---

## ✅ Business Recommendations
- Promote top-selling coffees (Latte, Cappuccino, Americano with Milk)
- Introduce offers on low-performing days (Monday & Wednesday)
- Focus on customer retention for high-frequency buyers
- Use the ML model for sales forecasting and inventory planning

---

## 🚀 Future Enhancements
- Add customer demographic data
- Extend analysis to full-year data
- Apply time-series forecasting models
- Deploy interactive dashboards
