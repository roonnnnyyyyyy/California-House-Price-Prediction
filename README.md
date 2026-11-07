# California House Price Predictor (Linear Regression)
**Maincrafts Technology AI/ML Internship - Task 1**

## Project Overview
This repository contains an end-to-end Machine Learning pipeline that predicts housing prices in California based on neighborhood features. The project demonstrates data ingestion, exploratory data analysis (EDA), model training, and performance evaluation using a Linear Regression algorithm.

## Deliverables Included
* `House_Price_Prediction.ipynb`: Complete Python workflow including data preprocessing, correlation heatmaps, and model evaluation.
* `Task1_Report.pdf`: Executive summary covering statistical insights, performance metrics, and strategic recommendations for model improvement.

## Tech Stack
* **Language:** Python
* **Libraries:** `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Google Colab

## Key Insights & Performance
* **Primary Driver:** Identified Median Income (`MedInc`) as the strongest positive correlate (0.69) to housing prices via Pearson correlation heatmap.
* **Accuracy Metrics:** Achieved an $R^2$ score of 0.576, a Mean Absolute Error (MAE) of 0.533, and a Root Mean Squared Error (RMSE) of 0.746.
* **Conclusion:** The linear model establishes a solid baseline but is limited by non-linear geographic factors and a $500,000 artificial data cap in the target variable. Upgrading to a tree-based model (e.g., Random Forest) is recommended for future iterations to capture complex market patterns.
