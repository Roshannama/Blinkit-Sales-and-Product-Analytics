# Blinkit-Sales-and-Product-Analytics

##  Overview

This project focuses on analyzing retail sales and outlet performance data inspired by Blinkit’s quick-commerce model. The goal is to transform raw transactional data into meaningful business insights that can support decision-making around inventory, expansion, and customer satisfaction.
Instead of just building charts, this project emphasizes **understanding patterns, identifying inefficiencies, and recommending actions**.

##  Objectives

* Analyze customer purchasing behavior across product categories
* Evaluate outlet performance based on size, type, and location
* Identify high and low-performing segments
* Build a data-driven foundation for business recommendations

##  Tech Stack
* **SQL** → Data cleaning, transformation, KPI computation
* **Python (Pandas, Matplotlib)** → Data preprocessing and exploratory analysis
* **Excel** → Initial validation and quick aggregation
* **Power BI** → Interactive dashboard and storytelling

##  Dataset Description

The dataset contains structured retail data with the following attributes:
* Product details (type, fat content, identifier)
* Sales information (revenue, visibility)
* Customer feedback (ratings)
* Outlet metadata (location tier, size, type, establishment year)

##  Data Preparation
Key preprocessing steps included:

* Standardizing inconsistent categorical values (e.g., fat content labels)
* Handling missing values using statistical imputation techniques
* Removing duplicates and validating data integrity
* Structuring data for efficient aggregation and visualization

##  Key Metrics (KPIs)
* **Total Sales** → Overall revenue performance
* **Average Sales** → Sales efficiency per item
* **Number of Items** → Dataset scale and product diversity
* **Average Rating** → Customer satisfaction indicator

##  Analysis Performed

### 1. Product-Level Insights

* Compared revenue contribution across item categories
* Identified high-demand and low-performing product segments

### 2. Fat Content Impact

* Evaluated how product composition (low-fat vs regular) affects sales

### 3. Outlet Performance

* Analyzed sales distribution by outlet size, type, and location
* Studied performance trends based on establishment year

### 4. Geographic Trends

* Compared revenue across Tier 1, Tier 2, and Tier 3 cities

##  Dashboard Highlights (Power BI)

* Interactive filters for outlet size, location, and item type
* Drill-down capability for deeper exploration
* KPI cards for quick performance overview
* Visual comparisons across multiple business dimensions

##  Key Insights

* Medium-sized outlets showed higher efficiency compared to larger ones
* Tier 2 and Tier 3 locations contributed significantly to revenue
* Essential and frequently purchased categories dominated sales
* Some categories underperformed, indicating scope for targeted improvement

##  Business Recommendations

* Focus expansion on high-performing outlet segments
* Optimize inventory based on category demand patterns
* Improve visibility and promotion of underperforming products
* Leverage customer ratings to enhance service quality

##  Project Structure

```
Blinkit-Analysis/
│── data/                  # Raw dataset (Excel/CSV)
│── sql/                   # SQL queries for analysis
│── python/                # EDA scripts / notebooks
│── dashboard/             # Power BI file (.pbix)
│── reports/               # Insights and summary documents
│── README.md
```


##  Learning Outcomes

* Applied end-to-end data analysis workflow
* Strengthened SQL aggregation and window function concepts
* Gained hands-on experience in BI dashboard development
* Improved ability to translate data into business insights

##  Future Improvements

* Incorporate time-series forecasting for demand prediction
* Add customer segmentation analysis
* Integrate real-time data pipelines
* Enhance dashboard with advanced DAX measures


