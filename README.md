# 📦 Warehouse & Inventory Optimization Model

## 📌 Project Overview
In fast-paced logistics environments like **FMCG**, stockouts lead to lost revenue and operational delays. This project applies **Data Science** to inventory management by automating the "Reorder Point" logic and predicting stockout risks using Machine Learning.

## 🎯 Key Features
- **Statistical Reorder Points (ROP):** Calculated optimal stock levels based on average daily demand and supplier lead times.
- **Machine Learning Risk Assessment:** Trained a **Random Forest Classifier** to identify high-risk SKUs based on supplier reliability and days of cover.
- **Strategic Prioritization:** Segmented inventory by unit cost to ensure high-value assets receive priority oversight.

## 🛠️ Technical Workflow
![Inventory Analysis Chart](inventory_bubble_chart.png)
1. **Data Cleaning:** Processed a 500-SKU dataset to calculate "Days of Cover."
2. **Modeling:** Built a risk-prediction engine with Scikit-Learn.
3. **Visualization:** Created a multi-dimensional Bubble Chart (Demand vs. Stock vs. Cost) to provide management with an at-a-glance operational health check.

## 📈 Business Impact
- **Efficiency:** Reduces manual shelf-counting by flagging the ~30% of items actually needing restock.
- **Cost Savings:** Prevents overstocking of low-demand items while protecting high-value assets.
- **Reliability:** Integrates supplier performance data into the procurement cycle.
