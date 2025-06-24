# 🧠 NLP Lab Exercises

This repository contains a series of hands-on lab exercises focused on core concepts and techniques in **Natural Language Processing (NLP)**. Each folder contains a specific lab with a script or notebook, input/output examples, and instructions.

---

## 📚 Table of Contents

| Lab | Title | Techniques Covered |
|-----|-------|--------------------|
| [01](./01_text_cleaning_tokenization) | Text Cleaning and Tokenization | Lowercasing, punctuation removal, stemming, lemmatization |
| [02](./02_stopword_removal_stemming) | Stopword Removal and Stemming | Tokenization, stopword filtering, Lancaster stemming |
| [03](./03_nlp_pipeline_classification) | NLP Pipeline with Classification | End-to-end preprocessing + ML model (scikit-learn) |
| [04](./04_ner_ngrams_dependency_parsing) | N-grams, NER & Dependency Parsing | BERT-based NER, spaCy NER, bigrams, POS tagging |
| [05](./05_srl_and_wsd_dialogue_analysis) | Semantic Role Labeling & WSD | spaCy SRL, Lesk WSD, dialogue input |
| [06](./06_chatbot_tfidf) | Chatbot with TF-IDF | Predefined and dynamic chatbot responses using cosine similarity |

---

## 🛠️ Requirements

Ensure you have the following installed:

```bash
pip install nltk spacy scikit-learn transformers stanza torch
python -m spacy download en_core_web_sm


Also download necessary NLTK corpora:

import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
