# DataCamp Projects

This repository contains a collection of machine learning and data science projects completed for DataCamp. Each project demonstrates different techniques, workflows, and tools for solving real-world problems. Every folder includes its own dataset, Jupyter notebook, and README with specific instructions.

## Projects Included

- **From Data to Dollar - Insurance Charges**

  - Explores and predicts insurance charges using regression models.
  - Involves data cleaning, feature engineering, and model validation.
  - Tools used:
    - **pandas**: Data manipulation, cleaning, and feature engineering.
    - **numpy**: Numerical operations and calculations.
    - **scikit-learn**: Preprocessing (StandardScaler), modeling (LinearRegression), validation (cross_val_score).
  - Files: `insurance.csv`, `validation_dataset.csv`, `notebook.ipynb`, `README.md`

- **Credit Card Approval**

  - Predicts credit card approvals using logistic regression and hyperparameter tuning (GridSearchCV).
  - Covers data preprocessing, model training, and evaluation.
  - Tools used:
    - **pandas**: Data loading, cleaning, and manipulation.
    - **numpy**: Handling missing values and numerical operations.
    - **scikit-learn**: Model selection (train_test_split), preprocessing (StandardScaler), modeling (LogisticRegression), metrics (confusion_matrix), hyperparameter tuning (GridSearchCV).
  - Files: `cc_approvals.data`, `notebook.ipynb`, `README.md`

- **Review Categorization**

  - Categorizes text reviews using natural language processing (NLP) and unsupervised learning (TF-IDF, KMeans clustering).
  - Includes text preprocessing, feature extraction, clustering, and analysis of top terms per category.
  - Tools used:
    - **pandas**: Data manipulation and analysis.
    - **numpy**: Numerical operations.
    - **scikit-learn**: Feature extraction (TF-IDF), clustering (KMeans).
    - **nltk**: Tokenization and stopword removal for text preprocessing.
  - Files: `reviews.csv`, `notebook.ipynb`, `README.md`

- **Word Frequency in My Blog**

  - Analyzes word frequency in blog posts written by Ankit Regmi ([blog](https://medium.com/@Ankit__/this-is-the-basic-outline-of-training-and-testing-a-model-84c2d3206bb8)).
  - Fetches blog content, parses HTML, preprocesses text, and visualizes word frequency.
  - Tools used:
    - **requests**: Fetches web content for analysis.
    - **BeautifulSoup**: Parses HTML and extracts readable text.
    - **nltk**: Tokenization and stopword removal.
    - **collections.Counter**: Efficient word frequency counting.
  - Files: `notebook.ipynb`, `README.md`

- **Face Recognition - Tabular Data**
  - Classifies faces (Arnold Schwarzenegger vs. non-Arnold) using tabular data features extracted from images.
  - Involves data loading, preprocessing, feature selection, and model training/evaluation.
  - Tools used:
    - **pandas**: Data loading, cleaning, and manipulation.
    - **numpy**: Numerical operations.
    - **scikit-learn**: Modeling, evaluation, and possibly feature selection.
  - Files: `data/lfw_arnie_nonarnie.csv`, `notebook.ipynb`

## How to Use

1. Explore each project folder for its own README and Jupyter notebook.
2. Open the notebook in Jupyter or VS Code and follow the step-by-step analysis.
3. Install required Python packages as listed in each project's README.

## Requirements

- Python 3.x
- See each project's README for specific package requirements (commonly pandas, numpy, scikit-learn, nltk, requests, beautifulsoup4)
