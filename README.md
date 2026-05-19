# Customer Churn Prediction & Retention Analytics
Predictive customer churn analytics project combining machine learning, feature engineering, and business intelligence reporting to improve customer retention.

## Project Overview

This project focuses on analysing customer churn behaviour for a subscription-based pet supply business, **Ted & Poppy**, with the objective of identifying key churn drivers and developing data-driven retention strategies.

Using predictive analytics, machine learning, customer behaviour analysis, and business intelligence techniques, this project explores how demographic, behavioural, product, and engagement variables influence customer retention outcomes.

The project combines:
- Data cleaning & preparation
- Feature engineering
- Exploratory data analysis
- Predictive modelling
- Churn classification
- Business intelligence reporting
- Customer retention recommendations

The final solution was designed to support business stakeholders in reducing churn, improving customer engagement, and increasing customer lifetime value.

---

# Business Problem

Ted & Poppy operates a subscription-based pet food service model where customer retention is critical to long-term profitability.

The company was experiencing increasing customer churn rates, creating risks for:
- recurring revenue,
- customer lifetime value,
- subscription stability,
- and long-term growth.

The primary goal of this project was to:
1. Identify the most important factors contributing to customer churn
2. Build predictive models capable of classifying churn risk
3. Generate actionable retention recommendations for the business

---

# Dataset Overview

The project used customer subscription and behavioural datasets containing:

- **200,000 customer observations**
- **29 variables**
- Demographic information
- Customer engagement metrics
- Subscription details
- Product purchase behaviour
- Survey responses
- Customer support interactions

The dataset included both:
- structured customer data
- behavioural engagement variables

The final churn rate observed in the dataset was approximately **15.9%**.

---

# Key Analytical Techniques

## Data Preparation
- Data cleaning and transformation
- Handling missing values
- Feature encoding
- Data validation
- Feature engineering
- Exploratory data analysis

## Predictive Modelling
Multiple machine learning models were developed and compared, including:

- Logistic Regression
- Random Forest
- LightGBM
- Gradient Boosting

## Model Evaluation
Models were evaluated using:
- Accuracy
- ROC-AUC
- Sensitivity & Specificity
- Confusion Matrix
- Predictive Value metrics

---

# Key Findings

The analysis identified several strong churn indicators, including:

- Days since last web purchase
- Customer satisfaction ratings
- Support ticket activity
- Discount dependency
- Geographic location patterns

The project revealed that churned customers generally:
- had lower engagement levels,
- longer inactivity periods,
- lower satisfaction ratings,
- and lower overall purchase value.

---

# Model Performance

The top-performing models achieved strong predictive performance:

| Model | Accuracy | ROC-AUC |
|------|------|------|
| LightGBM | 87.9% | 90.7% |
| Logistic Regression | 88.5% | 90.1% |
| Random Forest | 91.0% | 73.4% |

LightGBM provided the strongest balance between predictive accuracy and churn classification capability.

---

# Business Recommendations

Based on the findings, several retention strategies were proposed:

- Proactive customer re-engagement campaigns
- Personalised retention offers
- Improved customer support responsiveness
- AI-assisted support interactions
- Location-based marketing strategies
- Reduced dependency on excessive discounting
- Loyalty and gamification initiatives

These recommendations aimed to reduce churn risk while improving long-term customer retention and profitability.

---

# Tools & Technologies

## Programming & Analytics
- R
- Python

## Machine Learning
- LightGBM
- Random Forest
- Logistic Regression
- Gradient Boosting

## Data Analysis & Visualisation
- Power BI
- ggplot2
- dplyr
- tidyverse

## Data Preparation
- Feature Engineering
- ETL-style workflows
- Data Cleaning & Transformation

---

# Repository Structure

```bash
├── data/
│   ├── raw datasets
│   ├── cleaned datasets
│
├── notebooks/
│   ├── exploratory analysis
│   ├── feature engineering
│   ├── model development
│
├── visualisations/
│   ├── charts
│   ├── dashboards
│   ├── poster visuals
│
├── models/
│   ├── churn prediction models
│
├── reports/
│   ├── final poster
│   ├── business insights
│
├── README.md
