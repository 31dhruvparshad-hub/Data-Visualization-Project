# Data-Visualization-Project
# Sales Data Visualization (Python + Power BI)
about the Project
Hi! Dhruv Parshad, a final-year Electronics and Communication Engineering student. I built this project to make dataset cleaning and visualization easier for anyone dealing with raw data.

This project analyzes **2,800+ sales records** to uncover business insights using Python (Pandas, NumPy, Seaborn, Matplotlib) and Power BI.

## 📌 Project Overview
- Cleaned and explored sales data
- Engineered features (e.g., **gender detection** from customer first names)
- Visualized trends by **product line**, **deal size**, **country**, and **monthly sales**
- Exported **summary stats** to CSV/Excel
- Built an **interactive Power BI dashboard**

## 🔧 Tech Stack
- Python: Pandas, NumPy, Seaborn, Matplotlib, OpenPyXL (for Excel export)
- Power BI
- CSV/Excel for storage

## 📂 Structure
```
sales-data-visualization/
 ┣ data/sales_data.csv
 ┣ notebooks/sales_analysis.ipynb
 ┣ powerbi/Sales_Dashboard.pbix  (add your .pbix here)
 ┣ figures/  (auto-saved charts)
 ┣ requirements.txt
 ┗ README.md
```

## 🚀 How to Run
1) Install dependencies
```bash
pip install -r requirements.txt
```
2) Open the notebook
```
jupyter notebook notebooks/sales_analysis.ipynb
```
3) Run cells top-to-bottom. Charts will be saved into `figures/` and summary CSV/Excel into `data/`.

## 🧠 Highlights to Mention (Resume/Interview)
- **Pandas** for cleaning, **NumPy** for EDA, **feature engineering** like gender inference
- **Seaborn/Matplotlib** charts (monthly sales, product-line revenue, country heatmaps)
- **Power BI** dashboard with slicers & drilldowns
- **Exports**: CSV + Excel summaries

## 📈 Next Ideas
- Add forecasting (Prophet/ARIMA)
- RFM segmentation and cohort analysis
- Streamlit web app for interactive EDA
