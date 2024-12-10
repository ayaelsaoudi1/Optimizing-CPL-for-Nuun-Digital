# Optimizing CPL for Nuun Digital

## Overview
This repository contains the implementation of a project focused on optimizing Cost Per Lead (CPL) for Nuun Digital using machine learning techniques. The project aims to enhance marketing efficiency through predictive modeling, feature impact analysis, and actionable optimization strategies.

## Abstract
The project explores the application of machine learning techniques to predict and optimize CPL. Various models, including linear regression, decision trees, and neural networks, were evaluated to determine the most effective approach. The neural network emerged as the best-performing model, achieving high R-squared values and low error metrics, effectively capturing complex, non-linear relationships within the data. Feature impact analysis using SHAP values highlighted the significant influence of key features, such as the total number of leads and total marketing spend, on CPL. Optimization tasks provided actionable recommendations, enabling more efficient resource allocation and improved lead acquisition strategies.

## Data
The dataset used for this project contains **14,737 rows** of digital marketing metrics provided by Nuun Digital. Key data categories include:

- **Campaign and Platform Information**: Metrics like `Social Media/Platform`, `Industry`, `Location`, etc.
- **Campaign Performance Metrics**: `Impressions`, `Clicks`, `Ad Cost`, `CTR (%)`, `CPC ($)`, etc.
- **Engagement and Action Metrics**: `Certain Action`, `Sales`, `Revenue`, `Engagements`, etc.
- **Financial Metrics**: `Total Marketing Spend`, `CPL ($)`, `CPA ($)`, `ROI (%)`, etc.
- **Additional Metrics**: `Content/Ad Format`, `Device Type`, `Time of Day`, etc.

The dataset was preprocessed using **Label Encoding** for categorical variables and split into training, validation, and test sets (70%/15%/15%).

## Results

### Linear Regression:
- **MAE**: 10.33
- **R²**: 0.68
- Stable but less accurate compared to other models.

### Decision Tree:
- **MAE**: 0.80
- **R²**: 0.997
- Excellent fit but more suitable for classification tasks.

### Neural Network:
- **Final Loss**: 0.45 (test)
- **MAE**: 0.74, **MSE**: 0.90, **RMSE**: 0.95
- **R²**: 0.999
- Demonstrated the best overall performance, capturing data nuances effectively.

---

For further details and code implementation, explore this report:  
[Aya El Saoudi - MSBA Capstone Report](Aya_El_Saoudi_MSBA_Capstone_Report.pdf)
