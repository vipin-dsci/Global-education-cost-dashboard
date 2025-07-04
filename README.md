# 🌍 Global Education Cost Dashboard

This Power BI dashboard explores global education costs using data sourced from Kaggle. The dashboard provides insights into tuition fees, living costs, and total annual education expenses across countries, cities, and program levels.

## 📊 Dashboard Overview

The report consists of **2 main pages** and **6 tooltip pages**:

### Page 1: Education Cost Overview
- **Annual Education Cost** breakdown by **country** and **program level**
- Highlights of:
  - **Most Expensive Programs**
  - **Cheapest Programs**
- Tooltip page for detailed insights per program
- **Living Cost Breakdown**:
  - Segregated by **rent** and **living expenses**
  - Interactive **world map**
- **5 KPI Cards**:
  - Total Universities
  - Average Tuition Fees
  - Average Living Costs
  - Cheapest Options
  - Accommodation Stats
- Some KPI is linked to its **own tooltip page**
- **Filters Available**:
  - Country & City
  - Program
  - Level

### Page 2: Program Cost Deep Dive
- Detailed comparison of **program tuition fees**
- Dynamic **line chart** showing annual program cost by **country and city**
- **Table of Total Expenses per Year** categorized by program level
- Spotlight on:
  - **Most Expensive Programs**
  - **Cheapest Programs**
- Linked tooltip pages for further exploration
- **Same 3 filters**: Country & City, Program, Level

## 🗂 Dataset Source

- Orginal dataset from Kaggle: (https://www.kaggle.com/datasets/adilshamim8/cost-of-international-education)
## 📁 Cleaned Dataset

- The cleaned dataset used for this dashboard is available here:  
  [`cleaned_education_cost_data.csv`](Cleaned_International_edu_cost.csv)

### Cleaning Summary:
- Removed rows with `0` values
- Filtered incomplete or null entries.
- Standardized column formatting and ensured numeric consistency.

## 📁 Files in This Repo

- `Global_Education_Cost_Dashboard.pbix`: Power BI dashboard file
- 
### Page 1 Preview
![Overview](Global_education_cost_dashboard_page1.jpg)
### Page 2 Preview
![Program Cost](Global_education_cost_dashboard_page2.jpg)


## 🧠 Key Insights

- Compare costs of higher education globally with context-aware filters.
- Understand how living costs impact total education expenses.
- Identify affordable and premium programs across regions.

---
