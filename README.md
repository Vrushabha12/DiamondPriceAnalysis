# 💎 Diamond Price Prediction with Machine Learning

This project builds regression models to predict the price of diamonds based on their physical and quality attributes using **Linear Regression** and **Random Forest** algorithms.

## 📁 Dataset

The dataset is based on the classic **diamonds.csv** dataset, which includes the following features:

- **Numerical**: `carat`, `depth`, `table`, `x`, `y`, `z`
- **Categorical**: `cut`, `color`, `clarity`
- **Target**: `price`

## 🧠 Features

- 📦 Upload CSV via **Google Colab**
- 🧹 Automatic preprocessing:
  - One-hot encoding of categorical features
  - Train-test split
- 🧪 Model Training:
  - Linear Regression
  - Random Forest Regressor
- 📊 Evaluation Metrics:
  - RMSE
  - R² Score
- 📈 Visualization:
  - Actual vs Predicted Price scatter plot
- 📁 Export:
  - Trained model as `.pkl`
  - Predictions as `.csv`

## 🚀 How to Run (Google Colab)

1. Upload your `diamonds.csv` file when prompted.
2. The notebook will:
   - Train two models
   - Evaluate their performance
   - Plot results
   - Export and download the best model (`Random Forest`)
3. Files downloaded:
   - `diamond_price_model.pkl`
   - `diamond_price_predictions.csv`

## 📉 Sample Output

| Model             | RMSE     | R² Score |
|------------------|----------|----------|
| Linear Regression | ~1135    | ~0.919   |
| Random Forest     | ~640     | ~0.974   |

📈 Random Forest clearly outperforms Linear Regression and is selected as the final model.

## 🛠 Requirements

```bash
pandas
numpy
matplotlib
scikit-learn
joblib
