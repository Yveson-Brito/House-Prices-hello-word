# House Prices - Kaggle Beginner Project

## Objective

Predict house prices using machine learning with the Kaggle House Prices dataset.

Dataset:

House Prices - Advanced Regression Techniques

[Kaggle Competition Page](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques?utm_source=chatgpt.com)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## What Was Done

* Loaded CSV files
* Explored dataset structure
* Analyzed missing values
* Checked feature correlations
* Created visualizations
* Built a basic machine learning model
* Evaluated predictions using MAE

---

## Example Analysis

Main correlations with `SalePrice`:

* OverallQual
* GrLivArea
* GarageCars
* GarageArea
* TotalBsmtSF

---

## Project Structure

```text id="1klt1u"
train.csv
test.csv
notebook.ipynb
README.md
```

---

## Example Code

```python id="dzm11z"
import pandas as pd

train = pd.read_csv(
    '/kaggle/input/competitions/house-prices-advanced-regression-techniques/train.csv'
)

train.head()
```

---

## Model

Basic model used:

```python id="wy7nb1"
RandomForestRegressor
```

---

## Metrics

Metric used:

```python id="od8eu2"
Mean Absolute Error (MAE)
```

---

## Notes

This project was created for learning purposes and beginner practice in:

* data analysis
* machine learning
* exploratory data analysis (EDA)
* data cleaning
* model training
