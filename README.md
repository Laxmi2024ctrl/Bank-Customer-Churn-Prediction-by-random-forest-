# Bank Customer Churn Prediction using Random Forest

## Problem Statement
Predict which bank customers are likely to churn (leave the bank) using machine learning to help banks take proactive retention measures.

## Dataset
- **Source:** Bank Customer Churn Dataset
- **Records:** 10,000 customers
- **Features:** Credit Score, Age, Balance, Products, Active Member, Estimated Salary

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn (Random Forest, GridSearchCV, LabelEncoder)
- Matplotlib, Seaborn

## Project Workflow
1. Data Loading & Exploration
2. Label Encoding for categorical features
3. Train-Test Split (80-20)
4. Random Forest Classifier training
5. Hyperparameter Tuning (10 to 500 trees)
6. Cross-validation & Model Evaluation

## Results
- **Best Accuracy: 86.04%** at 300 trees
- **Cross-validation Mean Accuracy: 85.86%**
- **OOB Score: 85.94%**

## Key Insights
1. Age is the strongest predictor of churn
2. Customers with fewer products are more likely to churn
3. Inactive members have significantly higher churn rate
4. Germany has higher churn rate compared to France and Spain

## File Structure
​```
bank-churn-random-forest/
│
├── Random_Forest_prediction.ipynb   # Complete analysis notebook
└── README.md
​```

## How to Run
1. Clone the repository
2. Upload Bank Customer Churn Prediction.csv dataset
3. Open notebook in Google Colab or Jupyter
4. Run all cells sequentially
