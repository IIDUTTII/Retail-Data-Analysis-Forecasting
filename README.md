# retail-data-analysis-forecasting
# Hardware Store Inventory Optimization, Sales Analysis & Forecasting stocks for next day

## 📋 Project Overview

A comprehensive data analytics project for **Thakur Das and Sons**, a hardware retail shop in Himachal Pradesh, as part of IIT Madras BDM Capstone Project. The project focused on solving real-world inventory management problems using data science techniques.

## 🎯 What I Did

### 1. Data Collection & Business Understanding
- **Primary Data Collection**: Spent 3 months collecting daily sales and inventory data from a local hardware store
- **Business Problem Identification**: Identified key challenges like deadstock accumulation, seasonal demand variations, and poor inventory control
- **Stakeholder Engagement**: Worked directly with shop owner Mr. Pushap Raj to understand business operations

### 2. Data Analysis & Processing
- **Dataset**: 2,847 transactions over 61 days (Sep-Nov 2024)
- **Revenue Analyzed**: ₹13,47,751 across 11 product categories
- **Data Cleaning**: Standardized product categories, handled missing values, removed outliers
- **Statistical Analysis**: Calculated means, standard deviations, correlation coefficients

### 3. Key Analytics Performed

#### 📊 Descriptive Analytics
- Sales performance analysis across different product categories
- Profit margin calculations for each product line
- Inventory turnover rate analysis

#### 📈 Trend Analysis  
- Identified seasonal patterns in sales data
- Monthly decline of 16% from September to November
- Weather impact correlation (-0.73 with temperature)

#### 🎯 ABC Classification
- Categorized products based on revenue contribution
- Category A: 4 products generating 80% of revenue
- Category C: Taking 18.3% inventory space but only 5% revenue

#### 🔮 Predictive Modeling
- **Linear Regression Model** for demand forecasting
- Predicted winter demand decline of 31% on average
- Model accuracy: R² = 0.68, MAPE = 12.3%

## 🔍 Key Insights Discovered

### Business Performance
- **Declining Trend**: 16% revenue drop from Sep to Nov 2024
- **High Variability**: Some products had coefficient of variation >60%
- **Seasonal Impact**: Construction materials heavily affected by weather
- **Profit Distribution**: Structure materials (67.8% volume, 18.5% margin) vs Toiletry items (8.2% volume, 45.6% margin)

### Inventory Problems
- **Deadstock Issue**: ₹4.2 lakhs tied up in slow-moving inventory
- **Poor Resource Allocation**: Category C products consuming 18% space for 5% revenue
- **Seasonal Mismatch**: Maintaining peak inventory during low-demand winter months
- **Stock Imbalance**: 24 days of tile inventory vs optimal 7-10 days

### Market Patterns
- **Peak Season**: September (construction season)
- **Demand Drivers**: Local construction activity, weather conditions, festivals
- **High-Risk Products**: Tiles (CV=64%), Glass (CV=65%), Wash Basins (CV=78%)
- **Stable Products**: Cement (CV=27%), Bricks (CV=37%)

## 🛠 Technical Implementation

### Tools Used
- **Python** for data analysis and modeling
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for visualizations
- **Scikit-learn** for regression modeling
- **Excel** for initial data organization

### Methodologies Applied
- **Time Series Analysis** for trend identification
- **Correlation Analysis** for product relationships
- **Linear Regression** for demand prediction
- **Statistical Testing** for significance validation
- **ABC Analysis** for inventory classification

## 📈 Predictive Model Results

### Stock Prediction Model
- **Model Type**: Linear Regression
- **Target Variable**: Monthly sales quantity
- **Features**: Time, seasonality, product category
- **Performance**: 68% variance explained (R²=0.68)

### Winter Demand Forecasts
- **December**: 35% reduction in tile sales
- **January**: 58% reduction predicted  
- **February**: 78% reduction expected
- **Overall**: 31% average decline across categories

## 💡 Recommendations Provided

### Immediate Actions
1. **Inventory Reduction**: Cut Category C products by 40%
2. **Seasonal Planning**: Reduce winter procurement by 30%
3. **Focus Shift**: Prioritize Category A products (Bricks, Cement, Saria)

### Strategic Changes
1. **Automated Reordering**: Implement data-driven reorder points
2. **Predictive Planning**: Use regression models for procurement
3. **Space Optimization**: Reallocate storage based on ABC classification

### Expected Impact
- **₹4.5 lakhs** working capital freed up
- **25%** reduction in deadstock
- **15%** improvement in profit margins

## 🎓 Academic Context

### IIT Madras BDM Project
- **Course**: Business Data Management Capstone
- **Duration**: Sep 2024 - Feb 2025
- **Project Type**: Primary data analysis with real business impact
- **Evaluation**: Proposal → Mid-term → Final Report → Viva Voce

### Learning Outcomes
- Applied statistical methods to real business problems
- Developed end-to-end data science project experience
- Created actionable insights for business stakeholders
- Built predictive models with practical applications

## 📊 Files in Repository

```
📁 Analysis:
├── Proposal Report.pdf      # Initial project proposal
├── Mid-term Report.pdf      # Progress and preliminary findings  
└── Final Report.pdf         # Complete analysis and recommendations
```

## 🤝 Stakeholders

- **Business Partner**: Thakur Das and Sons Hardware Store
- **Academic Institution**: IIT Madras Online Degree Program
- **Project Supervisor**: Dr. Aditya Chandel, Dr. Ashwin J. Baliga
- **Industry Application**: Local hardware retail industry in Himachal Pradesh

