#  Boston Housing Price Prediction with XGBoost

This is a small machine learning project where I tried to predict house prices using the **Boston Housing dataset**.  
The goal was to go through the full ML workflow step by step: cleaning the data, exploring it, training a model, and checking how well it performs.  

I chose **XGBoost Regressor** because it’s one of the most popular and powerful algorithms for tabular data.

---

## What’s inside this project
- **Data preprocessing**  
  Loaded the dataset from OpenML, fixed categorical columns, and checked for missing values.  

- **Data analysis**  
  Looked at basic statistics, correlation heatmap, feature distributions, and a few pairplots to see how variables relate to house prices.  

- **Model training**  
  Split the dataset into train and test sets (80/20) and trained an XGBoost regression model.  

- **Evaluation**  
  Measured performance using Mean Absolute Error (MAE) and R² score.  
  Also plotted:
  - Actual vs Predicted prices  
  - Residuals distribution  
  - Feature importance  

---

## Results
On the test set, the model performs pretty well:  
- **MAE:** around 2.0 – 2.5  
- **R²:** usually between 0.88 and 0.92  

That means the model explains most of the variance in house prices, though not perfectly (which is expected with this dataset).

