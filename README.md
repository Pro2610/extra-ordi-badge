From Spend to Strategy: ROMI Analysis in Python
# 📊 ROMI Analysis of Marketing Campaigns with Python

This project focuses on analyzing the performance of marketing campaigns based on advertising spend and revenue data.  
The main metric calculated is **ROMI (Return on Marketing Investment)** — a key indicator for evaluating the effectiveness of ad campaigns.

---

## 🔧 Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset Overview

The dataset includes:
- `ad_date`: Date of ad activity
- `campaign_name`: Name of the marketing campaign
- `total_spend`: Advertising costs
- `total_value`: Revenue generated

---

## 🔎 Project Workflow

1. **Convert dates** to datetime format
2. **Filter data** for the year 2021
3. **Group data** by campaign
4. **Calculate ROMI**:  
   \[(total_value - total_spend) / total_spend\]
5. **Create visualizations**:
   - Daily ad spend and ROMI (with 7-day moving averages)
   - Total spend by campaign (bar chart)
   - ROMI distribution (boxplot, histogram)
   - Correlation heatmap
   - Linear regression: spend vs revenue

---

## 📈 Key Visuals

### Daily ROMI in 2021
### Correlation Heatmap

## 💡 Key Insights

- Campaigns with the **highest ROMI** aren’t necessarily those with the **highest total spend**.
- There is a **strong correlation** between ad spend and revenue, but with diminishing returns in some cases.
- Monitoring **days with negative ROMI** is essential to optimize budget allocation.

---
