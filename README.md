# Natural-Language-Processing-Exercise
# Exercise 1: Text Cleaning and Tokenization

This exercise demonstrates basic NLP preprocessing techniques such as:

- Converting text to lowercase
- Removing punctuation and numbers
- Removing stopwords
- Tokenizing words and sentences
- Applying stemming and lemmatization

### 📁 Files

- `nlp1.py`: Python script for text preprocessing. Accepts user input and returns:
  - Tokens
  - Sentences
  - Cleaned (stemmed and lemmatized) text

### 🛠️ Libraries Used

- `nltk`
- `re`
- `string`

Ensure you have the required NLTK corpora by running:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
