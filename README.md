# Predictive Ecommerce Analytics

![Python](https://img.shields.io/badge/Python-Analytics-blue)
![Plotly](https://img.shields.io/badge/Plotly-Visualization-purple)
![Dash](https://img.shields.io/badge/Dash-Dashboard-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)

---

## 🔗 Quick Links

- 📊 [Project Overview](#project-overview)
- 🎯 [Business Problem](#business-problem)
- 🎯 [Objectives](#objectives)
- 🗄️ [Dataset Description](#dataset-description)
- 🛠️ [Tools & Technologies](#tools--technologies)
- ⚙️ [Project Workflow](#project-workflow)
- 📱 [Dashboard Overview](#dashboard-overview)
- 👥 [Customer Experience Analysis](#customer-experience-analysis)
- 📦 [Product Intelligence Analysis](#product-intelligence-analysis)
- 🏪 [Seller Intelligence Analysis](#seller-intelligence-analysis)
- 🌎 [Geographic Analysis](#geographic-analysis)
- 📈 [Revenue Trend Analysis](#revenue-trend-analysis)
- 🔮 [Predictive Analytics](#predictive-analytics)
- 🧠 [Key Insights](#key-insights)
- 💼 [Business Impact](#business-impact)
- 🚧 [Challenges Faced](#challenges-faced)
- 📚 [Key Learnings](#key-learnings)
- 📂 [Project Structure](#project-structure)
- 📬 [Contact](#contact)

---

# Project Overview

Predictive Ecommerce Analytics is an end-to-end data analytics project built using Python to analyze customer behavior, delivery performance, product performance, seller contribution, geographic demand patterns, and future revenue growth within an e-commerce marketplace.

The project combines exploratory data analysis, advanced business intelligence visualizations, interactive dashboards, and machine learning forecasting to generate actionable business insights.

---

# Business Problem

E-commerce companies generate massive volumes of transactional data every day.

Businesses often struggle to answer critical questions such as:

- What factors drive customer satisfaction?
- Which product categories generate the highest revenue?
- Which sellers contribute the most to the marketplace?
- Which states drive the majority of revenue and orders?
- How will future revenue grow based on historical trends?

This project addresses these questions through data-driven analytics and predictive modeling.

---

# Objectives

- Analyze customer satisfaction trends
- Measure delivery performance impact on reviews
- Identify high-performing product categories
- Evaluate seller contribution and concentration
- Discover geographic demand trends
- Analyze revenue growth patterns
- Forecast future revenue using Machine Learning
- Build an executive-level analytics dashboard

---

# Dataset Description

### Domain
E-Commerce

### Dataset
Brazilian E-Commerce Public Dataset (Olist)

### Records
~100,000 Orders

### Key Tables

- Orders
- Customers
- Products
- Order Items
- Reviews
- Payments
- Sellers
- Geolocation Data

---

# Tools & Technologies

### Programming & Analytics

- Python
- Pandas
- NumPy

### Visualization

- Plotly
- Plotly Express
- Matplotlib

### Machine Learning

- Scikit-Learn
- Linear Regression

### Dashboard Development

- Dash

### Environment

- Jupyter Notebook

---

# Project Workflow

1. Data Cleaning
2. Data Integration
3. Feature Engineering
4. Exploratory Data Analysis
5. Customer Analytics
6. Product Analytics
7. Seller Analytics
8. Geographic Analytics
9. Revenue Trend Analysis
10. Revenue Forecasting
11. Dashboard Development

---

# Dashboard Overview

The project includes an interactive analytics dashboard developed using Dash.

## Dashboard Home

![Dashboard](images/Dashboard%201.png)

## KPI Overview

![Dashboard KPI](images/Dashboard%201.1.png)

## Revenue Monitoring View

![Dashboard Revenue](images/Dashboard%201.2.png)

### Key Features

- Revenue Monitoring
- Customer Metrics
- Order Metrics
- Delivery Performance Tracking
- Geographic Analysis
- Revenue Trend Monitoring

---

# Customer Experience Analysis

## Business Question

How does delivery performance affect customer satisfaction?

### Customer Satisfaction vs Delivery Performance

![Customer Satisfaction](images/Customer%20Satisfaction%20vs%20Delivery%20Performance.png)

### Key Finding

- Early deliveries receive the highest review scores.
- Customer satisfaction drops significantly when deliveries are delayed.
- Delivery performance is one of the strongest drivers of customer experience.

---

### Average Review Score by Delivery Group

![Review Score](images/Average%20Review%20Score%20by%20Delivery%20Group.png)

### Key Finding

- Review scores remain above 4.0 for early and on-time deliveries.
- Late deliveries reduce average ratings below 2.0.
- Operational efficiency directly impacts customer perception.

---

### Customer Experience Correlation Heatmap

![Correlation Heatmap](images/Customer%20Experience%20Correlation%20Heatmap.png)

### Key Finding

- Delivery metrics show measurable relationships with customer reviews.
- Customer satisfaction is influenced more by delivery experience than pricing variables.

---

# Product Intelligence Analysis

## Business Question

Which product categories drive marketplace performance?

### Category Intelligence Matrix

![Category Intelligence](images/Category%20Intelligence%20matrix.png)

### Key Finding

- Product categories differ significantly in revenue generation.
- High-volume categories are not always the highest revenue categories.
- Strategic category positioning is essential for growth.

---

### Premium Category Analysis

![Premium Category](images/Premium%20Category%20Analysis.png)

### Key Finding

- Several categories generate premium revenue despite lower sales volume.
- Premium categories offer opportunities for higher margins.
- Pricing strategies should vary by category characteristics.

---

# Seller Intelligence Analysis

## Business Question

How concentrated is marketplace revenue among sellers?

### Seller Performance Analysis

![Seller Performance](images/Seller%20Performance.png)

### Key Finding

- Revenue is highly concentrated among a relatively small number of sellers.
- Top-performing sellers contribute a disproportionate share of total marketplace revenue.
- Seller segmentation can help identify strategic partnership opportunities.

---

# Geographic Analysis

## Business Question

Which regions contribute the most to marketplace performance?

### Revenue by State

![Revenue by State](images/Revenue%20by%20States.png)

### Key Finding

- A small number of states account for the majority of marketplace revenue.
- Geographic concentration creates expansion opportunities in underpenetrated regions.

---

### Orders by State

![Orders by State](images/Orders%20by%20State.png)

### Key Finding

- Order distribution closely follows revenue distribution.
- High-volume states remain critical drivers of marketplace activity.

---

### Revenue per Order by State

![Revenue per Order](images/Revenue%20per%20Order%20by%20states.png)

### Key Finding

- Certain states generate significantly higher revenue per transaction.
- Customer purchasing behavior differs across regions.

---

# Revenue Trend Analysis

## Business Question

How has marketplace revenue evolved over time?

### Monthly Revenue Trend

![Monthly Revenue](images/Monthly%20Revenue%20Trend.png)

### Key Finding

- Marketplace revenue demonstrates strong growth over the observed period.
- Revenue acceleration indicates increasing platform adoption.

---

### Revenue Trend and Moving Average

![Moving Average](images/Revenue%20trend%20and%20moving%20average.png)

### Key Finding

- The moving average smooths short-term fluctuations.
- Long-term revenue momentum remains positive.
- Growth trends are sustainable rather than driven by isolated spikes.

---

# Predictive Analytics

## Business Question

What is the expected future revenue trend?

### Revenue Forecast Using Linear Regression

![Revenue Forecast](images/Revenue%20Trend%20Forcast%20using%20Linear%20regression.png)

### Methodology

- Monthly Revenue Aggregation
- Time Index Feature Engineering
- Linear Regression Modeling
- Revenue Prediction

### Key Finding

- Forecasting suggests continued marketplace growth.
- Historical trends indicate positive future revenue performance.
- The model provides a baseline estimate for future planning and budgeting.

---

# Key Insights

### Customer Experience

- Delivery delays significantly reduce review scores.
- Early deliveries consistently achieve higher customer satisfaction.

### Product Intelligence

- Revenue generation varies significantly across product categories.
- Premium categories generate high revenue despite lower sales volumes.

### Seller Intelligence

- Revenue is concentrated among a relatively small group of sellers.
- Top sellers dominate marketplace performance.

### Geographic Intelligence

- Revenue and orders are concentrated within a few states.
- Regional demand patterns reveal growth opportunities.

### Predictive Analytics

- Historical trends indicate sustainable marketplace growth.
- Revenue forecasts suggest continued expansion.

---

# Business Impact

This project enables organizations to:

- Improve customer satisfaction strategies
- Optimize delivery operations
- Identify profitable product categories
- Recognize high-performing sellers
- Support regional expansion planning
- Improve forecasting and budgeting
- Enable data-driven decision making

---

# Challenges Faced

- Integrating multiple datasets
- Handling missing and inconsistent data
- Designing business-focused KPIs
- Building advanced interactive visualizations
- Creating interpretable forecasting models

---

# Key Learnings

- End-to-End Data Analytics Workflow
- Data Cleaning & Feature Engineering
- Advanced Plotly Visualizations
- 3D Business Analytics
- Dashboard Development with Dash
- Machine Learning Forecasting
- Business Intelligence Storytelling

---

# Project Structure

```text
├── data/
├── images/
├── notebooks/
│   └── Predictive Ecommerce Analytics.ipynb
├── dashboard/
│   └── app.py
├── requirements.txt
└── README.md
```

---

# Contact

**Name:** Shaikh Mohd Israhil

**Email:** mohdisrahils@gmail.com

**LinkedIn:** https://www.linkedin.com/in/mohd-israhil-shaikh-3b8b04281/

**GitHub:** https://github.com/israhil10
