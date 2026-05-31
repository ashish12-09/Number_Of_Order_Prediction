## Project 2: Number of Orders Prediction

### Objective
Develop a machine learning model that predicts the 
number of customer orders for a restaurant meal 
delivery service based on historical data.

### Dataset
- Source: Kaggle (arashnic/food-demand)
- Records: 456,548 rows | 15 columns
- Period: 145 weeks (~3 years)
- Centers: 77 restaurant fulfillment centers

### Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, 
Scikit-learn, XGBoost, Jupyter Notebook

### Key Steps
- Merged 3 datasets (orders, centers, meals)
- Exploratory Data Analysis (5 visualizations)
- Feature engineering (discount %, promotion flag)
- Trained 3 ML models and compared performance

### Key Findings
- Email promotion nearly triples order volume
- Beverages is the most ordered category
- Italian cuisine leads in total orders
- Discounts increase orders by 41%
- Base price is the strongest predictor of demand

### Results
| Model             | MAE    | RMSE   |
|-------------------|--------|--------|
| Linear Regression | 200.35 | 342.92 |
| Random Forest     | 115.59 | 216.56 |
| XGBoost           | 126.47 | 222.07 |

---
