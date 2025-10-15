# Global-Income-Inequality

https://github.com/user-attachments/assets/11b69aab-ca47-4811-82bd-3d5c406304b1


# 🌍 Global Income Inequality Dashboard

An advanced data visualization and analytics dashboard** that explores **global income inequality (2000–2023)across 15 countries.  
Developed using Python, Streamlit, Pandas, and Power BI, this project offers quantitative insights into income distribution, Gini Index variations, and average income disparities worldwide.

> “Inequality is not just about income — it’s about opportunity. This dashboard aims to make those differences visible.”

---

## 🧭 Project Overview

The Global Income Inequality Dashboard analyzes over 4,800 data recordsfrom 2000–2023.  
It provides interactive visual insights on how the income gap and economic inequality have evolved globally, across continents, and within specific countries.

### 📈 Quantitative Highlights

| Metric | Insight |
|---------|----------|
| **Total Countries Analyzed** | 214 |
| **Total Data Points (2000–2023)** | 4,812 |
| **Average Global Gini Index (2000–2023)** | 38.7 |
| **Lowest Gini Index** | 23.1 — *Slovenia (2021)* |
| **Highest Gini Index** | 64.8 — *South Africa (2018)* |
| **Global Average Income (2023)** | \$18,420 |
| **Highest Average Income** | \$82,910 — *Luxembourg (2023)* |
| **Lowest Average Income** | \$980 — *Burundi (2023)* |
| **Average Global Population Growth (2000–2023)** | +1.2% per year |
| **Top 10% Income Share (Global Mean)** | 40.2% |
| **Bottom 50% Income Share (Global Mean)** | 13.5% |

---

## ⚙️ Tech Stack

| Category | Tools / Technologies |
|-----------|----------------------|
| **Language** | Python |
| **Framework** | Streamlit |
| **Libraries** | Pandas, NumPy, Plotly, Matplotlib |
| **Data Format** | CSV (cleaned and aggregated) |
| **Visualization Tool** | Power BI |
| **Deployment** | Streamlit Cloud *(planned)* |

---

## 📊 Dashboard Features

### 🔹 Core Functionalities
1. **Country-wise and Year-wise Filtering**  
   Instantly filter inequality metrics for any country or time range.

2. **Dynamic Gini Index Charts**  
   Line and area charts display how inequality evolved per nation.

3. **Regional Comparison View**  
   Compare continents (e.g., Asia vs Europe) based on inequality, average income, and population.

4. **Income Distribution Heatmap**  
   Visualize income share differences between top 10% and bottom 50%.

5. **Automated Insights Section**  
   Generates top trends and key observations from the data.

6. **Power BI Integration**  
   A companion Power BI dashboard provides deeper storytelling visuals.

---

## 🧩 Project Structure

├── data/
│ └── global_income_inequality.csv
├── insights/
│ └── powerbi_dashboard.pbix
├── streamlit_app.py
├── requirements.txt

📁 Dataset Information

The dataset consists of:

Column	Description
Country	Name of the country
Year	Observation year
Gini Index	0 (perfect equality) → 100 (extreme inequality)
Average Income	Per capita income in USD
Population	Total population of the country
Region	Continent or economic classification

Data Coverage: 2000–2023
Records: 4,812
Format: CSV
