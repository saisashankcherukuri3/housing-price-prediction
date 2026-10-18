# Housing Price Prediction

Trained a Ridge Regression model on the Ames Housing dataset to predict home sale prices.

## Results
- **R² Score:** 0.86
- **RMSE:** $33,384
- **Dataset:** 2,930 homes, 77 features after cleaning

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## What I Did
- Dropped columns with >50% missing values and imputed remaining nulls with median
- Encoded all categorical columns with LabelEncoder
- Trained Ridge Regression (alpha=10) with an 80/20 train-test split
- Visualized actual vs. predicted prices, top 15 feature importances, and sale price distribution

## Key Finding
Overall Quality (`OverallQual`) was the single most influential feature — far outweighing location, size, or year built.

## Dataset
[Ames Housing Dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
