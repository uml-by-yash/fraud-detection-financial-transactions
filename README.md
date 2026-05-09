# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions. Built this as part of my B.E. IT academics at LDRP-ITR, KSV.

---

## About the Project

The dataset has around 2.8 lakh transactions and out of those only 492 are fraud which means its really imbalanced. So the main challenge here was not just building a model but making sure it can actually catch the rare fraud cases without getting confused by the huge number of normal ones.

I used SMOTE to fix the imbalance and then trained a Random Forest model on top of that. Also made a Power BI dashboard to show things visually.

---

## Steps I followed in the notebook

1. Imported all the required libraries
2. Loaded the dataset
3. Did Exploratory Data Analysis to understand the data
4. Cleaned the data wherever needed
5. Visualized the class imbalance
6. Separated features (X) and target (y)
7. Applied SMOTE to balance the classes
8. Split into train and test sets
9. Trained a Random Forest model
10. Evaluated the model performance using precision, recall and F1 score

---

## Dataset

- Source: Kaggle (Credit Card Fraud Detection)
- Total transactions: 2,84,807
- Fraud cases: 492 only
- Features: V1 to V28 (PCA transformed), Time, Amount
- Target column: Class (0 = normal, 1 = fraud)

---

## Tools and libraries used

- Python (Google Colab)
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib, seaborn
- Power BI (for dashboard)

---

## Folder structure

```
├── notebooks/        --> colab notebook
├── dashboard/        --> power bi dashboard file
├── data/             --> dataset files
└── README.md
```

---

Made by Yash
B.E. IT — LDRP-ITR, KSV (2025-26)
