# Teen Mental Health Depression Prediction

Machine Learning Model Training & Improvement
AI Course — Assignment #1 | 5th Semester — Spring 2026

## Dataset
- **Source:** Kaggle - Teen Mental Health Dataset
- **Records:** 1,000 rows
- **Features:** 12 + 1 target
- **Target:** depression_label (Binary: 0=No Depression, 1=Depression)

## Model
- **Algorithm:** Random Forest Classifier
- **Best Accuracy:** 93.00%
- **Improvements:** GridSearchCV + SMOTE + 10-Fold CV

## Project Structure
├── data/           # Dataset
├── notebooks/      # Jupyter notebook
├── models/         # Saved model
├── reports/        # PDF report
└── images/         # Flowchart & charts

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 93.00% |
| Precision | 93.07% |
| Recall | 93.00% |
| F1-Score | 93.00% |

## Top Predictors
1. anxiety_level
2. stress_level
3. addiction_level