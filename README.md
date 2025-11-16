# 🍫 Chocolate Analysis: Customer Segmentation & Purchasing Analysis

## 📋 Project Overview

This project performs customer segmentation analysis on chocolate purchasing behavior. It combines exploratory data analysis (EDA) with machine learning clustering techniques to identify distinct customer groups and understand their purchasing patterns across different chocolate brands.

## 📁 Project Structure

```
Chocolate_Project/
├── README.md                    # Project documentation 
├── EDA.ipynb                    # Exploratory Data Analysis notebook
├── Segmentation.ipynb           # Customer Segmentation & Analysis notebook
├── purchase data.csv            # Raw purchase transaction data 
├── segmentation data.csv        # Customer demographic data 
└── merged_dataset.csv           # Final merged dataset with customer segments 
```

## 📊 Data Description

### Segmentation Data (`segmentation data.csv`)
Contains demographic information for 2000 unique customers:
- **ID**: Customer identifier
- **Sex**: 0 = Male, 1 = Female
- **Marital status**: 0 = Single, 1 = Married/Divorced
- **Age**: Customer age 
- **Education**: 0 = Unknown, 1 = High School, 2 = University, 3 = Graduate School
- **Income**: Annual income 
- **Occupation**: 0 = Unemployed, 1 = Employed, 2 = Self-Employed
- **Settlement size**: 0 = Small, 1 = Medium, 2 = Big

### Purchase Data (`purchase data.csv`)
Contains transaction records with:
- **ID**: Customer identifier
- **Day**: Day of purchase event
- **Incidence**: 1 = Purchase made, 0 = No purchase
- **Brand**: Chocolate brand (1-5, or 0 if no purchase)
- **Quantity**: Units purchased
- **Last_Inc_Brand**: Brand purchased by the customer on their previous visit
- **Last_Inc_Quantity**: Units purchased by the customer on their previous visit
- **Price_1 to Price_5**: Prices for brands 1-5
- **Promotion_1 to Promotion_5**: Promotion status for each brand
- **Demographic fields**: Sex, Marital status, Age, Education, Income, Occupation, Settlement size

## 🔬 Analysis Notebooks

### 1. EDA.ipynb – Exploratory Data Analysis

Covers comprehensive data exploration, including:
- Customer Demographics
- Product & Pricing Insights

### 2. Segmentation.ipynb – Customer Segmentation & Predictive Analysis

Applies machine learning techniques for customer segmentation:

- Data Preprocessing
- Dimensionality Reduction (PCA) 
- Clustering using K-Means 
- Data Visualization

**Analysis Output:**
- Cluster characteristics and statistical summaries
- Demographics comparison across segments
- Brand preference by segment
- Purchase behavior analysis
- Revenue contribution by segment and brand
"# Chocolate-Sales-and-Customer-Segmentation-" 
