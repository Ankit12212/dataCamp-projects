# Word Frequency in My Blog

This project analyzes the frequency of words in blog posts written by me ([blog](https://medium.com/@Ankit__/this-is-the-basic-outline-of-training-and-testing-a-model-84c2d3206bb8)). The goal is to explore the most common words and gain insights into writing patterns and content focus.

## Folder Contents

- `notebook.ipynb`: Jupyter notebook containing code for loading, processing, and analyzing blog text

## Project Workflow

1. **Text Loading**: Uses the `requests` library to fetch blog content from the web.
2. **HTML Parsing**: Uses `BeautifulSoup` to parse and extract text from HTML.
3. **Text Preprocessing**:
   - Uses `nltk` for tokenization and stopword removal.
   - Converts all words to lowercase and removes punctuation using `RegexpTokenizer`.
4. **Word Frequency Analysis**:
   - Uses `collections.Counter` to count word occurrences after removing stopwords.
   - Displays the top most frequent words in the blog.

## Tools Used

- **requests**: Fetches web content (your blog post) for analysis.
- **BeautifulSoup**: Parses HTML and extracts readable text from the blog page.
- **nltk (Natural Language Toolkit)**: Provides tools for tokenizing text and removing common stopwords, making the analysis more meaningful.
- **collections.Counter**: Efficiently counts word frequencies in the processed text.

## Requirements

- Python 3.x
- requests
- beautifulsoup4
- nltk

## Usage

1. Open `notebook.ipynb` in Jupyter or VS Code.
2. Run the cells to:
   - Fetch and process your blog text
   - Tokenize and clean the text
   - Analyze and display word frequency results
