# StreamFlow Churn Analysis  
*Identifying drivers of subscriber churn in the Standard tier*

## Overview  
**Objective**: This project aimed to uncover why Standard tier users of StreamFlow, a subscription-based streaming platform, were churning at a high rate. The goal was to derive actionable insights that could inform product improvements and retention strategies.  
**Context**: Using user-level subscription data, I performed exploratory data analysis (EDA) to examine behaviours, usage patterns, as well as self-reported reasons for churn. The analysis focused on identifying the key differentiators between churned and retained users within the Standard tier.

## Key Insight  
A significant pattern emerged: **58% of churned Standard tier users accessed the service via mobile devices**, compared to just 40% of overall users. This indicates potential **usability issues on mobile platforms**, making mobile experience a critical area for improvement. Additionally, most users who churned cited reasons like price dissatisfaction and finding better alternatives, rather than content availability — meaning UX and perceived value are key drivers.

## Tools & Technologies  
- **Python**: `pandas`, `numpy`  
- **Data Visualization**: `seaborn`, `matplotlib`  
- **Development Environment**: Visual Studio Code  
- **Documentation**: Jupyter Notebook (.ipynb), Word (.docx)

## Techniques Used  
- Exploratory Data Analysis (EDA)  
- Feature comparisons across churned vs. retained groups  
- Subgroup analysis (Standard tier segmentation)  
- Behavioral metric analysis (device usage, session length, content engagement)  
- Business metric estimation (ARPU, monthly revenue impact)

## Key Metrics  
- **Churn Rate**: 23.4% for Standard users  
- **Length of Subscription**: Average churn point around 6 months  
- **Primary Reasons for Churn**: Better alternatives, pricing dissatisfaction  
- **Device Usage**: High churn correlation with mobile device use

## Business Impact  
If churn is reduced from 23.4% to 15% through mobile UX improvements, StreamFlow could recover up to **$3,345.77 annually** from Standard users.  
Additionally, offering an annual discounted plan could increase retention beyond the 6-month churn peak, improving both revenue and financial predictability. This strategy could increase yearly revenue by **$2,023.95** and strengthen long-term user satisfaction.

## Files in This Repo  

| File | Description |
|------|-------------|
| `EDA for Churn data.ipynb` | Main Jupyter Notebook with full analysis |
| `Final written report.docx` | Written summary submitted for evaluation |
