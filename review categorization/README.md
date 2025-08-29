# Review Categorization Project

This project uses machine learning and natural language processing (NLP) to automatically categorize text reviews. The workflow includes:

- Loading and exploring a dataset of reviews
- Preprocessing text (tokenization, stopword removal)
- Feature extraction using TF-IDF
- Clustering reviews into categories using KMeans
- Analyzing top terms for each category

## Folder Contents

- `reviews.csv`: Dataset containing text reviews and scores
- `notebook.ipynb`: Jupyter notebook with code, step-by-step analysis, and results

## Project Workflow

1. **Data Loading & Exploration**: The notebook loads `reviews.csv` and samples/reviews the data.
2. **Text Preprocessing**: Reviews are tokenized and cleaned using NLTK (stopword removal, word tokenization).
3. **Feature Engineering**: TF-IDF vectorization is applied to convert text into numerical features.
4. **Clustering**: KMeans is used to group reviews into categories based on their content.
5. **Analysis**: The notebook identifies top terms for each category and visualizes/prints results.

## Requirements

- Python 3.x
- pandas, numpy, scikit-learn
- nltk (for text preprocessing)

## Usage

1. Open `notebook.ipynb` in Jupyter or VS Code.
2. Run the cells in order to:
   - Preprocess and vectorize the reviews
   - Cluster reviews and assign categories
   - Analyze and interpret the results
