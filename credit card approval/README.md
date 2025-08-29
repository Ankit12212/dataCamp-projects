# Credit Card Approval Project

This project focuses on predicting credit card approvals using machine learning techniques. It includes data cleaning, preprocessing, model training, and evaluation.

## Folder Contents

- `cc_approvals.data`: Raw dataset for credit card approvals
- `notebook.ipynb`: Jupyter notebook with code, analysis, and results

## Project Workflow

1. **Data Cleaning & Preprocessing**: Handles missing values and encodes categorical variables using pandas and numpy.
2. **Feature Engineering**: Uses pandas to transform and prepare features for modeling.
3. **Model Training**: Applies logistic regression from scikit-learn to predict approvals.
4. **Model Evaluation**: Uses confusion matrix and cross-validation to assess model performance.
5. **Hyperparameter Tuning**: Utilizes GridSearchCV from scikit-learn to optimize model parameters.

## Tools Used

- **pandas**: For data loading, cleaning, manipulation, and feature engineering.
- **numpy**: For numerical operations and handling missing values.
- **scikit-learn**:
  - `train_test_split`: Splits data into training and test sets.
  - `StandardScaler`: Scales features for better model performance.
  - `LogisticRegression`: Builds the classification model.
  - `confusion_matrix`: Evaluates model predictions.
  - `GridSearchCV`: Performs hyperparameter tuning to find the best model settings.

## Requirements

- Python 3.x
- pandas, numpy, scikit-learn (install via pip if needed)

## Usage

Run the notebook to:

- Load and clean the credit card approval dataset
- Build and evaluate machine learning models
- Analyze results and insights

## Author

Ankit Regmi

## License

This project is for educational purposes.
