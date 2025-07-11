# 🛒 Supermarket Sales Dashboard (Power BI)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Interactive Power BI professional dashboard of Q1 2019 supermarket sales - data cleansing in LibreOffice Calc, modeling in SQLite, analysis with DAX and visuals designed for decision‑makers.

**Interactive analysis of supermarket retail sales in the first quarter of 2019**  

## 📊 Project overview

This project offers a comprehensive interactive Power BI dashboard that analyzes 1,000 real transactions from a supermarket chain with three branches (Yangon, Naypyitaw, and Mandalay) between January and March 2019. It shows the data processing from start to finish:

 **Dataset download** from Kaggle:  
   https://www.kaggle.com/datasets/willianoliveiragibin/market-sales-data

## 🖼️ Dashboard preview

![Dashboard Preview](images/Market_Sales_Dashboard.png)

## 🛠 Tools Used

- **LibreOffice Calc** – Data cleaning & column creation
- **SQLite (via Anaconda CLI)** – Data modeling & SQL queries
- **Power BI Desktop** – Power Query transformation + DAX visual analysis

## 📁 Project structure

market-sales-dashboard/
│
├── docs/                            # Dashboard files
│   ├── Market_sales_dashboard.pdf   # Exported Power BI report (PDF)
│   └── Market_sales_dashboard.pbix  # Power BI project file
│
├── images/                          # Visual resources
│   └── Market_Sales_Dashboard.png   # Screenshot preview of the dashboard
│
├── README.md                        # Main documentation file
└── LICENSE                          # MIT license for open use

## 📈 Key Business Metrics

| KPI                     | Value      |
|-------------------------|------------|
| Total Sales (USD)       | $322,967   |
| Tax Collected (USD)     | $15,380    |
| Units Sold              | 5,510      |
| Avg. Ticket Value       | $322.97    |

Highlights:
- Branch C leads with $111K in sales
- Top categories: Food & Beverages, Sports & Travel, Electronic accessories
- Customer type: Member
- Total Units Sold by Product line

## 📊 General Business Interpretation

This analysis allows a supermarket to:

- Identify the most profitable product lines by revenue and units.
- Compare branch performance and make investment decisions.
- Analyze behavior by customer type (loyalty).
- Evaluate the average ticket for campaigns or price adjustments.

## 📌 Key Insights and Recommendations

This dashboard provides actionable insights that a supermarket chain can use to drive strategic decisions and optimize operations across its three branches.

### 🏪 Branch Performance

- **Branch C (Mandalay)** generated the highest revenue ($111,000), accounting for approximately **34%** of total Q1 sales.
  - 📌 **Recommendation**: Prioritize marketing efforts and promotional campaigns in Branch C to strengthen its leading position and test high-performing product launches.

### 📦 Product Line Profitability

- **Food & Beverages** and **Electronic Accessories** were the most profitable product lines by both revenue and volume.
  - 📌 **Recommendation**: Increase inventory and create bundle offers or discounts in these categories to boost average basket size and repeat purchases.

### 👥 Customer Type Behavior

- **Member customers** consistently showed a **higher average ticket value** compared to non-members.
  - 📌 **Recommendation**: Strengthen loyalty programs to encourage registration and repeat visits, particularly in underperforming branches.

### 📅 Temporal Sales Patterns

- While the dataset does not include precise month-by-month sales timestamps, the analysis across the first quarter indicates stable demand across all product lines and branches.
  - 📌 **Suggestion**: In future datasets, integrating monthly or weekly time variables could uncover seasonal trends or promotional impacts, allowing the business to align campaigns with real consumption patterns.

### 💡 Executive Summary

> This analysis highlights where to invest marketing efforts, which product lines generate the highest ROI, and how customer segmentation can guide loyalty strategies. By replicating Branch C's success model in lower-performing locations, the supermarket could potentially increase average revenue per branch by **15–20%** over the next quarter.

## ℹ️ Notes

This project was created as a personal initiative to reinforce my technical skills in real-world data workflows. I executed the entire process from raw data to visual insights, including cleansing, modeling, and dashboard design.

I'm sharing it publicly to demonstrate my capabilities as a data analyst and my commitment to continuous learning.

Although based on a public dataset, the entire analysis was conducted with a business-oriented mindset, simulating the decision-making needs of a real retail organization.

## 👩‍💻 About Me

I’m María Brudas, a geologist with professional experience in geospatial data analysis, sediment modeling, and technical reporting. My background includes the integration of traditional geoscientific methods with digital tools for 3D facies modeling, spatial data processing, and field data management.

Recently, I’ve complemented my profile with formal training in data analytics—adding tools such as Power BI, SQL (SQLite), Python, and data visualization techniques to my workflow. This combination allows me to:

- Translate complex data into actionable insights  
- Apply analytical thinking to both scientific and commercial environments  
- Deliver clear, structured results through dashboards and reports

This dashboard project is part of my ongoing transition into the data analytics field. I’m currently open to opportunities that value multidisciplinary thinking, technical rigor, and a strong commitment to real-world problem solving.

📫 [LinkedIn Profile](https://www.linkedin.com/in/mariabrudas)  
🌍 Based in Buenos Aires, Argentina  
🚀 Open to freelance or full-time roles in BI, analytics, or data strategy.
