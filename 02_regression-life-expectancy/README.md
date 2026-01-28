# Assignment 2 – Regression (ML1)

## Task
Solve a regression problem predicting **life expectancy** based on country-level data.  
The dataset contained both numerical and categorical features, including missing and inconsistent values, which required preprocessing before model training.  

## Approach
- **Preprocessing:**  
  - Fixed inconsistent categorical values  
  - Handled invalid or out-of-range entries  
  - Imputed missing values
  - Removed low-predictive features (e.g., Population)  
  - Dropped high-cardinality feature `Country`  

- **Models:**  
  - Custom Random Forest (own implementation)  
  - Ridge Regression  
  - AdaBoost Regressor  

- **Evaluation:** RMSE on validation, test, and evaluation sets  

## Results
- Best model: **Random Forest**  
- Test RMSE: ~1.9  
- Evaluation set RMSE: **2.13** (above average performance; best in class was 2.03)  

## Files
- `regression_life_expectancy.ipynb` – Jupyter notebook with full solution  
- `data.csv` – training data  
- `evaluation.csv` – evaluation data  
- `results.csv` – predictions for evaluation data  
