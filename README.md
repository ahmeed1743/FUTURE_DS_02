# Product Advertising Data Analysis & Dashboard

## Overview

This project analyzes advertising spend data from multiple channels to understand their impact on product sales. Using a Kaggle dataset titled **“Product Advertising Data”**, the goal is to:

- Clean and explore advertising and sales data
- Calculate key marketing metrics such as total spend, revenue, and Return on Investment (ROI)
- Build a regression model to predict product sales based on ad spend across channels
- Use SHAP (SHapley Additive exPlanations) to explain feature importance in the model
- Visualize spend vs sales relationships and ROI distribution
- Provide interactive filtering of channels within a Jupyter Notebook
- Generate strategic marketing recommendations based on analysis

This project fulfills the requirements of the **Future Interns: Data Science & Analytics Task 2**.

---

## Dataset

- **Source:** [Product Advertising Data on Kaggle](https://www.kaggle.com/datasets/singhnavjot2062001/product-advertising-data)
- **Columns:**
  - `tv`: Ad spend on TV advertising
  - `billboards`: Ad spend on billboard advertising
  - `google_ads`: Ad spend on Google Ads
  - `social_media`: Ad spend on social media platforms
  - `influencer_marketing`: Spend on influencer marketing campaigns
  - `affiliate_marketing`: Spend on affiliate marketing
  - `product_sold`: Number of products sold (target variable)

---

## Project Structure

- `advertising.csv` - Raw dataset file
- `advertising_analysis.ipynb` - Jupyter Notebook containing full analysis:
  - Data loading and cleaning
  - Metric calculations (total spend, revenue, ROI)
  - Regression modeling and performance evaluation
  - SHAP explainability plots
  - Visualizations with matplotlib and seaborn
  - Interactive filters using ipywidgets
  - Strategic recommendations based on results

---

## Tools and Libraries Used

- Python 3.x
- pandas, numpy (Data manipulation)
- matplotlib, seaborn (Data visualization)
- scikit-learn (Regression modeling)
- shap (Model explainability)
- ipywidgets (Interactive filters in Jupyter Notebook)

---
