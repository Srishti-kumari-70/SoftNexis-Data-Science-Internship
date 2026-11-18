# Task 5: Machine Learning Modeling

## Objective
To build a complete machine learning classification pipeline using the Titanic dataset to predict passenger survival.

## Dataset
- Dataset: Titanic Dataset
- Original Records: 887
- Original Features: 8
- Target Variable: `Survived`

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Problem Definition and Dataset Exploration
2. Data Preprocessing
3. Feature Engineering
   - FamilySize
   - IsAlone
   - Title
4. Categorical Encoding and Feature Scaling
5. Train-Test Split (80:20)
6. Model Training
   - Logistic Regression
   - Random Forest
7. Model Evaluation
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
   - ROC-AUC
8. Feature Importance Analysis
9. Overfitting Analysis
10. 5-Fold Cross-Validation
11. Hyperparameter Tuning using GridSearchCV

## Final Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 82.02% | 78.46% | 73.91% | 76.12% | 87.16% |
| Original Random Forest | 74.72% | 67.14% | 68.12% | 67.63% | 79.51% |
| Tuned Random Forest | 79.21% | 75.00% | 69.57% | 72.18% | 83.28% |

## Best Model
Logistic Regression achieved the best overall test performance with:
- Accuracy: 82.02%
- F1-Score: 76.12%
- ROC-AUC: 87.16%

## Conclusion
This project demonstrates a complete machine learning workflow, including data preprocessing, feature engineering, classification, model evaluation, cross-validation, hyperparameter tuning, and model interpretation. Logistic Regression was selected as the final model based on its test-set performance.
