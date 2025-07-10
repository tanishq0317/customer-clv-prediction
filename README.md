# Customer Lifetime Value (CLV) Prediction

This project predicts the future value of customers over time using their past transaction data, including frequency, recency, and average order value.

### Models Used:
- BG/NBD (Beta Geometric / Negative Binomial Distribution)  
- Gamma-Gamma model (for monetary value estimation)

### Files
- `clv_script.py` → Main logic for training and prediction  
- `customer_clv_predictions.csv` → Final output: CLV for each customer  
- `requirements.txt` → All dependencies for running the project  

### Input Data
Uses the [Online Retail Dataset from Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
