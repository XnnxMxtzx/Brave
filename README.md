#Retail Demand & Inventory Analysis

## 📌 Project Overview

Retail businesses need to balance customer demand with available inventory. Too much inventory can increase holding costs, while too little inventory can lead to missed sales and stock shortages.

This project analyzes retail demand and inventory patterns across product categories, time periods, promotion status, and competitor pricing. The goal is to identify demand drivers, understand inventory gaps, and provide data-driven recommendations for better inventory and demand planning.

> **Note:** This is a portfolio project using a simulated dataset created for analytical practice. The analysis demonstrates how data analytics can be applied to a retail planning problem.

---

## 🎯 Problem Statement

The retail business currently has limited visibility into how demand varies across categories, seasons, promotions, and competitor pricing, making it difficult to determine the right inventory levels.

This analysis aims to identify the main demand patterns and inventory gaps so that the business can improve replenishment planning, prioritize high-demand categories, and better align inventory with customer demand.

---

## ❓ Business Questions

This project answers the following questions:

1. Which product categories have the highest average demand?
2. How does average inventory compare with average demand across categories?
3. How does demand change over time?
4. Do promotions appear to be associated with higher demand?
5. Is there a relationship between competitor pricing and demand?
6. How do units ordered compare with units sold across quarters?
7. Which areas should be prioritized for inventory and demand planning?

---

# 📊 Dashboard

The final Power BI dashboard provides an interactive view of retail demand and inventory performance.

![Retail Demand & Inventory Analysis Dashboard](dashboard.png)

### Dashboard KPIs

- **Total Units Sold:** 7M
- **Total Demand:** 8M
- **Average Demand:** 104.32
- **Average Inventory:** 301.06

The dashboard can be filtered by:

- Category
- Region
- Seasonality
- Promotion Status

---

# 🗂️ Data & Methodology

## Dataset

The dataset used in this project is a **simulated retail dataset** designed to represent common demand and inventory scenarios.

The dataset contains variables related to:

- Product Category
- Region
- Demand
- Inventory
- Units Ordered
- Units Sold
- Promotion Status
- Competitor Pricing
- Year
- Quarter
- Month
- Seasonality

The simulated nature of the dataset allows the project to demonstrate the complete analytics workflow without using confidential business information.

---

## 🔄 Analytical Process

### 1. Data Cleaning & Preprocessing

The data was reviewed and prepared before analysis.

The main preprocessing steps included:

- Checking for missing values
- Checking for duplicate records
- Standardizing categorical values
- Reviewing numerical fields for consistency
- Checking date and time fields
- Validating demand, inventory, units ordered, and units sold values
- Preparing the dataset for visualization and aggregation

---

### 2. Exploratory Data Analysis

Exploratory analysis was performed to understand:

- Demand by product category
- Inventory versus demand
- Demand trends over time
- Units ordered versus units sold
- Demand during promotion and non-promotion periods
- Competitor pricing versus demand

This helped identify patterns and potential areas where supply and demand may not be aligned.

---

### 3. Feature Engineering

Additional analytical fields were created or derived where needed, including:

- Year
- Quarter
- Month
- Promotion Status
- Category-level demand metrics
- Average inventory
- Average demand
- Average units ordered
- Average units sold

These fields were used to create the dashboard KPIs and visualizations.

---

### 4. Data Transformation

The data was transformed into aggregated measures suitable for dashboard analysis.

Examples include:

- Total Demand
- Total Units Sold
- Average Demand
- Average Inventory
- Average Units Ordered
- Average Units Sold

These measures allow demand and inventory performance to be compared across different business dimensions.

---

### 5. Root Cause Analysis

The analysis examined several possible drivers of demand:

**Promotion:**  
Demand was compared between promotional and non-promotional periods to understand whether promotions were associated with changes in demand.

**Competitor Pricing:**  
Competitor pricing was compared with total demand to identify whether pricing movements were associated with demand changes.

**Seasonality and Time:**  
Monthly and quarterly demand patterns were analyzed to identify periods of higher and lower demand.

**Category:**  
Category-level demand and inventory were compared to identify where inventory levels may not be aligned with customer demand.

---

# 🔎 Key Insights

## 1. Groceries have the highest average demand

Among the five categories analyzed, **Groceries recorded the highest average demand**, followed by Clothing and Electronics.

Furniture had the lowest average demand among the categories.

This suggests that category-level demand should be considered when planning inventory rather than applying the same inventory approach across all product categories.

---

## 2. Inventory levels vary significantly by category

The comparison between average inventory and average demand shows that inventory levels differ considerably across categories.

Groceries have both high demand and high inventory, while some lower-demand categories also maintain substantial inventory levels.

This indicates an opportunity to review inventory allocation based on actual demand patterns.

---

## 3. Demand changes significantly throughout the year

The monthly demand trend shows considerable variation throughout the year.

Demand starts at a high level in January, falls sharply in February, and then increases again during March.

Additional increases can be observed around June and August, followed by a decline toward October before demand increases again toward December.

This indicates that time-based demand patterns should be considered when planning inventory and replenishment.

---

## 4. Promotions are associated with higher average demand

The dashboard shows higher average demand during **promotion periods** compared with periods without promotions.

This suggests that promotions can be an important demand driver.

However, the relationship shown in this dashboard is descriptive and does not by itself prove that promotions caused the increase in demand.

---

## 5. Units ordered and units sold are relatively close

Across the quarters shown, average units ordered and average units sold follow similar patterns.

The relatively close movement between the two measures suggests that ordering activity generally follows sales demand.

However, differences between units ordered and units sold can still create opportunities to improve replenishment timing and inventory planning.

---

## 6. Competitor pricing shows an inverse pattern with demand in the dataset

The competitor pricing scatter plot shows that higher competitor pricing values are generally associated with lower observed demand values in the simulated dataset.

This suggests that competitor pricing may be an important variable to monitor when analyzing demand.

Further statistical testing would be needed before treating this relationship as causal.

---

# 💡 Recommendations

Based on the analysis, the following actions could help improve retail demand and inventory planning:

### 1. Prioritize high-demand categories

Give greater attention to categories such as **Groceries and Clothing**, which show higher average demand.

Inventory planning should consider category-level demand instead of using a single inventory strategy for all products.

### 2. Align inventory with demand patterns

Review categories where inventory appears high relative to demand.

The objective should be to maintain sufficient stock for customer demand while avoiding unnecessary excess inventory.

### 3. Use seasonal demand patterns in planning

The observed monthly fluctuations suggest that historical demand patterns can be incorporated into inventory planning.

Higher-demand periods should be considered when determining replenishment requirements.

### 4. Monitor promotional periods

Because average demand is higher during promotion periods in this dataset, inventory planning should account for expected promotional demand before launching campaigns.

This can help reduce the risk of inventory shortages during periods of increased demand.

### 5. Monitor competitor pricing

Competitor pricing should be included as one of the variables considered in demand analysis.

Changes in competitor prices can be monitored alongside demand to identify potential changes in customer purchasing behavior.

### 6. Improve demand and inventory monitoring

A recurring dashboard can help decision-makers monitor:

- Demand
- Inventory
- Units ordered
- Units sold
- Promotions
- Competitor pricing
- Seasonal trends

This creates a more consistent data-driven approach to inventory and demand planning.

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Excel** | Data review and initial validation |
| **Power BI** | Data transformation, analysis, visualization, and dashboard development |
| **GitHub** | Project documentation and portfolio presentation |

---

# 📈 Dashboard Highlights

The dashboard contains six main analytical views:

### Demand Trend Over Time
Shows total demand by month and highlights seasonal fluctuations.

### Average Demand by Category
Compares average demand across Groceries, Clothing, Electronics, Toys, and Furniture.

### Average Demand by Promotion Status
Compares demand during promotion and non-promotion periods.

### Competitor Pricing vs Demand
Examines the relationship between competitor pricing and total demand.

### Average Units Ordered vs Average Units Sold
Compares ordering and sales activity across quarters.

### Average Inventory vs Average Demand
Compares inventory levels with demand across product categories.

---

# 📚 Business Context

Effective retail inventory management requires balancing product availability with the cost of holding excess stock. Demand forecasting and inventory analysis can help businesses account for factors such as historical demand, seasonality, promotions, and changing customer behavior.  

IBM notes that demand forecasting can support inventory planning and help businesses manage demand fluctuations, stockouts, and carrying costs. :contentReference[oaicite:1]{index=1}

Oracle similarly describes retail inventory management as the process of maintaining enough inventory to satisfy demand while minimizing unnecessary inventory costs. :contentReference[oaicite:2]{index=2}

Research from McKinsey also highlights the importance of incorporating factors such as seasonality, promotions, pricing, and inventory visibility into retail planning. :contentReference[oaicite:3]{index=3}

---

# 🔗 References & Inspiration

### Project Structure Inspiration
This project was structured with reference to:

:contentReference[oaicite:4]{index=4}

### Additional References

- :contentReference[oaicite:5]{index=5}
- :contentReference[oaicite:6]{index=6}
- :contentReference[oaicite:7]{index=7}
- :contentReference[oaicite:8]{index=8}

---

# 👩‍💻 About This Project

This project was created as part of my data analytics portfolio to demonstrate my ability to translate a business problem into a data-driven analysis.

The project demonstrates skills in:

- Data cleaning
- Data preparation
- Exploratory data analysis
- Business analysis
- Root cause analysis
- KPI development
- Data visualization
- Power BI dashboard development
- Business storytelling

The main objective is not only to visualize data, but to turn the analysis into insights that can support better retail demand and inventory decisions.
