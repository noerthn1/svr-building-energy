# Support Vector Regression on Energy Efficiency Dataset

This project applies **Support Vector Regression (SVR)** to predict the **Heating Load (Y1)** of buildings based on architectural features.

## 📊 Dataset
- **Features (X):**
  - Relative Compactness  
  - Surface Area  
  - Wall Area  
  - Roof Area  
  - Overall Height  
  - Orientation  
  - Glazing Area  
  - Glazing Area Distribution  

- **Target (y):**
  - Heating Load (Y1)

Dataset Source: [UCI Energy Efficiency Dataset](https://archive.ics.uci.edu/ml/datasets/energy+efficiency)

## ⚙️ Methodology
- Preprocessing with `pandas` & `scikit-learn`
- Train-test split (80-20)
- Support Vector Regression (RBF kernel)

## 📈 Results
- **R² Score**: 0.92  
- **RMSE**: 2.82  
- **MAE**: 1.88  

![SVR Predicted vs Actual](images/svr_pred_vs_actual.png)

The model shows strong predictive performance, with points closely following the red reference line.

## 🔮 Future Work
- Test SVR with different kernels  
- Compare with Random Forest & XGBoost  
- Hyperparameter tuning (GridSearchCV)  

---
