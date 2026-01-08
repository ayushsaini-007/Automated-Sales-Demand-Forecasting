# 📈 Automated Sales & Demand Forecasting

This project provides a clear and simple sales demand forecasting solution using historical retail sales data. I analyzed store-level and product-family sales patterns along with transactional and economic indicators to estimate future demand. Goal: generate a baseline 30-day demand forecast to support inventory planning and business decision-making.

---

## 📌 What This Project Covers

- Loaded and explored historical retail sales dataset  
- Cleaned and merged sales, store, transaction, and oil price data  
- Handled missing values and ensured time-series consistency  
- Engineered lag and rolling average features (7, 14, 28 days)  
- Applied time-based train–validation split  
- Trained a regression-based machine learning model  
- Generated store–product level demand predictions  
- Aggregated predictions into a 30-day business-level forecast  
- Saved forecast outputs for reporting and portfolio use  

**Tools used:** Python, Pandas, NumPy, Scikit-learn, Matplotlib

---

## 📂 Folder Structure  

Automated-Sales-Demand-Forecasting/  
│── notebooks/  
│   └── Automated_Sales_Demand_Forecasting.ipynb  
│── outputs/  
│   ├── future_sales_forecast.csv   
│   └── sales_demand_forecast.png  
└── README.md  

---

## 📊 Key Insights

- Baseline 30-day demand forecast assumes stable future conditions  
- Recent sales history (lags and rolling averages) drives demand patterns  
- Product-family summaries highlight high-demand categories  
- Store-level summaries help identify locations with higher expected demand  

---

## 📈 Visual Highlights

- Line chart showing next 30-day total sales demand forecast  

---

## 🚀 How to Run This Project

1. Clone the repository.  
2. Open `notebooks/Automated_Sales_Demand_Forecasting.ipynb` in Jupyter Notebook.  
3. Run all cells to generate forecasts and outputs.  
4. Review results in the `/outputs` folder.

---

## 🧠 Business Use Cases

- Inventory planning and replenishment  
- Demand forecasting for procurement decisions  
- Store and product performance analysis  
- Baseline forecasting for retail operations  

---

🙋‍♂️ **Author**  
Ayush Saini  
Aspiring Data Analyst  
📧 ayushsaini8535@gmail.com  
