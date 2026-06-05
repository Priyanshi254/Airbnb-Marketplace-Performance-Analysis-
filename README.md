# Airbnb Marketplace Performance Analysis

## Overview

This project analyzes Airbnb listing data to understand marketplace patterns related to pricing, availability, guest satisfaction, and variable relationships.

Using Exploratory Data Analysis (EDA) and Correlation Analysis, the study investigates how listing characteristics vary across room types, neighborhood groups, pricing categories, and review metrics to uncover actionable marketplace insights.

---

## Business Problem

Airbnb listings differ significantly in terms of pricing, availability, location, and customer reviews. Understanding these variations is essential for identifying marketplace trends and evaluating factors associated with listing performance.

This analysis addresses the following questions:

- How do Airbnb prices vary across room types and neighborhood groups?
- How is listing availability distributed across different categories?
- How do review ratings vary across listings?
- What relationships exist among price, availability, reviews, ratings, and other variables?

---

## Dataset Information

The dataset contains **48,895 Airbnb listings** with information related to:

### Property Information
- Room Type
- Neighborhood Group
- Construction Year

### Pricing Information
- Price (USD)
- Service Fee (USD)

### Review Information
- Number of Reviews
- Reviews per Month
- Review Rating

### Availability Information
- Availability (365 Days)

---

## Analytical Approach

### 1. Data Cleaning & Preparation
- Handled missing values
- Removed duplicates
- Corrected data types
- Prepared dataset for analysis

### 2. Exploratory Data Analysis (EDA)
- Distribution Analysis
- Comparative Analysis
- Trend Identification

### 3. Pricing Analysis
- Average Price by Room Type
- Average Price by Neighborhood Group
- Price Distribution
- Price Variability Analysis

### 4. Availability Analysis
- Availability Distribution
- Availability by Room Type
- Availability by Neighborhood Group
- Availability vs Reviews
- Availability by Price Range

### 5. Customer Satisfaction Analysis
- Review Rating Distribution
- Rating Comparison Across Categories
- Review Activity Analysis

### 6. Correlation Analysis
- Correlation Matrix
- Variable Relationship Assessment
- Key Correlation Identification

---

## Key Findings

### Pricing Insights
- Entire homes/apartments have the highest average listing prices.
- Manhattan records the highest average prices among analyzed neighborhood groups.
- Most listings fall within mid-price categories.
- Price variability differs across room types.

### Availability Insights
- Availability levels vary significantly across listings.
- Entire homes/apartments show higher average availability.
- Availability patterns differ across neighborhood groups.
- No strong relationship exists between availability and review counts.

### Customer Satisfaction Insights
- Most listings receive ratings of 4 or higher.
- Review ratings vary across room types and locations.
- Review frequency shows only a limited relationship with ratings.

### Correlation Insights
- Strong positive correlation between service fee and price.
- Moderate positive correlation between reviews and reviews per month.
- Weak relationships exist between price, availability, and review ratings.
- Listing performance appears to be influenced by multiple factors rather than a single variable.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
Airbnb-Marketplace-Performance-Analysis/
│
├── Airbnb_Marketplace_Performance_Analysis.ipynb
├── Airbnb PPT.pdf
├── README.md
└── images/
    └── dashboard.jpeg
```

---

## Business Insights

- Pricing varies considerably across room types and neighborhood groups.
- Location plays an important role in marketplace positioning.
- Availability patterns differ across listing categories and locations.
- Review ratings cannot be explained by a single numerical variable alone.
- Multiple independent factors contribute to overall listing performance.

---

## Conclusion

This analysis provides a comprehensive view of Airbnb marketplace dynamics by examining pricing behavior, availability patterns, guest satisfaction, and variable relationships.

The findings highlight that marketplace performance is influenced by a combination of pricing, location, availability, and review-related factors, emphasizing the importance of a multi-dimensional analytical approach when evaluating Airbnb listings.

---
