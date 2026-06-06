# Customer Shopping Behavior Analysis

## Overview

Customer Shopping Behavior Analysis is an end-to-end Data Analytics project that explores customer purchasing patterns, spending behavior, product preferences, and revenue trends. The project demonstrates the complete analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, dashboard development, and business reporting.

The goal is to transform raw customer transaction data into actionable insights that can help businesses improve customer engagement, optimize marketing strategies, and support data-driven decision-making.

---

## Dataset

The dataset contains customer demographic information, purchasing behavior, product details, subscription status, ratings, discounts, and shipping preferences.

### Dataset Summary
- **Total Records:** 3,900
- **Total Features:** 18
- **Missing Values:** 37 (Review Rating column)
- **Categories:** Clothing, Accessories, Footwear, Outerwear

### Key Features
- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Review Rating
- Discount Applied
- Shipping Type
- Previous Purchases
- Purchase Frequency
- Season
- Size
- Color

---

## Tools & Technologies

### Programming & Analysis
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Database
- MySQL

### Visualization
- Power BI

### Reporting
- Microsoft PowerPoint
- Gamma AI

### Development Environment
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Performed initial data inspection and profiling.

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer demographics.
- Explored purchasing patterns and spending behavior.
- Evaluated revenue trends across categories.
- Examined subscription and discount usage.
- Generated visualizations to identify key insights.

### 3. Data Cleaning & Preprocessing
- Handled missing values.
- Standardized column names.
- Removed redundant fields.
- Created new features such as customer age groups.
- Prepared data for SQL analysis and dashboard development.

### 4. SQL Analysis (MySQL)
- Imported the cleaned dataset into MySQL.
- Wrote SQL queries to analyze:
  - Revenue by category
  - Sales performance
  - Customer segmentation
  - Subscription behavior
  - Product performance
  - Age-group analysis

### 5. Power BI Dashboard Development
- Created an interactive dashboard to visualize business metrics.
- Added KPI cards, charts, and slicers for dynamic analysis.

### 6. Reporting & Presentation
- Prepared a business insights report.
- Created a presentation using Gamma AI and PowerPoint.
- Summarized findings and recommendations for stakeholders.

---

## Dashboard
### Customer Behavior Dashboard

<img width="800" alt="Sales Performance" src="Customer Behavior Dashboard.png">


### Key Metrics
- Average Purchase Amount: $59.76
- Average Review Rating: 3.75
- Total Customers: 3.9K

### Key Metrics
- Average Purchase Amount: **$59.76**
- Average Review Rating: **3.75**
- Total Customers: **3.9K**

### Dashboard Visuals
- Subscription Status Distribution
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group

### Interactive Filters
- Gender
- Category
- Subscription Status
- Shipping Type

---

## Key Results

### Customer Insights
- Average customer spend is **$59.76** per purchase.
- Young Adults contribute the highest revenue.
- Customer spending is relatively consistent across age groups.

### Revenue Insights
- Clothing generates the highest revenue and sales volume.
- Accessories rank second in revenue contribution.
- Outerwear contributes the lowest revenue.

### Subscription Analysis
- Non-subscribers represent the majority of customers.
- Subscribers and non-subscribers have similar average purchase values.
- Subscription growth presents a potential business opportunity.

### Product Insights
- Top-performing products drive a significant share of sales.
- Certain products show strong dependence on discounts.
- Customer ratings remain relatively stable across products.

---

## Business Recommendations

- Increase subscription adoption through exclusive benefits.
- Strengthen loyalty programs for repeat customers.
- Optimize discount strategies to maintain profitability.
- Focus marketing efforts on high-value customer segments.
- Promote top-selling and highly rated products.

---

## Project Deliverables

- Python EDA Notebook
- Cleaned Dataset
- MySQL Query File
- Power BI Dashboard
- Business Report
- Gamma AI Presentation
- PowerPoint Presentation

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/brijeshkumarbaghel/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

### Run the Jupyter Notebook

```bash
jupyter notebook Customer-Shopping-Behavior-Analysis.ipynb
```

### Execute SQL Queries

1. Import the cleaned dataset into MySQL.
2. Open the SQL script.
3. Run the queries to generate business insights.

### Open Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the dataset if required.
3. Explore the dashboard using slicers and filters.

---

## Conclusion

This project showcases a complete Data Analytics workflow, combining Python, MySQL, and Power BI to analyze customer shopping behavior and generate business insights. The findings help identify revenue drivers, customer segments, and growth opportunities, demonstrating practical skills in data analysis, SQL querying, dashboard development, and business reporting.
