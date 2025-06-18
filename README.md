# Text_Preprocessing_Project_with_NLTK
Text preprocessing on a single sentence using NLTK

**1.Introduction**

This project is a natural language processing (NLP) pipeline developed in Python using NLTK, spaCy and scikit-learn. The aim is to apply various preprocessing steps on given texts, perform grammatical analysis and make the text more meaningful by identifying important words.

 # 2.Steps taken

1. **Text Cleaning & Preprocessing**
- Preventing case inconsistencies with lowercasing.
- Cleaning punctuation and special characters.
- Removing numbers and unnecessary spaces.
- Tokenization: Splitting the text into words (tokens).
- Stopword Removal: Removing common words that do not carry any meaning, such as “and”, “an”, “but”.
- Stemming: Reducing words to their roots (e.g., “running” → “run”).
- Lemmatization: Converting the word to its basic form in the dictionary (finding more accurate and contextual roots).

2. **POS Tagging (Part-of-Speech Tagging)**
- Determining the grammatical type of each word using NLTK (noun, verb, adjective, adverb, etc.).
- Filtering of relevant POS types (e.g. creating a meaningful word set by taking only nouns, verbs and adjectives).

3. **Named Entity Recognition (NER) - Special Name Recognition** - Detection of special entities such as person names, organizations, places, dates in the text with the spaCy library.
- Determination of the type (label) of each entity (e.g. PERSON, ORG, GPE etc.).

4. **Chunking (Noun Phrase Extraction)** - Determination of noun phrases using spaCy's noun chunking feature.
- In this way, meaningful word groups in the text (e.g. "New York City") are easily extracted.

5. **TF-IDF (Term Frequency-Inverse Document Frequency) Calculation** - Calculation of the importance of words in the text with the scikit-learn library.
- With TF-IDF, not only frequently occurring but also meaningful words in the document are highlighted.
- Listing of the first 5 most meaningful words with their scores.

6. **Additional Features and Improvements**
- Use and customization of different stopword lists.
- Richer analysis using SpaCy and NLTK models together.
- Reducing noise in the text with token-based filters.
- Preparing the necessary infrastructure for advanced grammatical analysis and context-oriented operations.

# 3-Results

**The application provides the following types of outputs on sample texts:**

Cleaned, stemmed and lemmatized words.

Grammatical type of each word (noun, verb, adjective etc.).

List of proper nouns and their types.

Extraction of meaningful noun phrases.

TF-IDF scores of the most important words.
  

