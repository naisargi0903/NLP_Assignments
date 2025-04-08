# SEM 6: NLP_Assignments

## Overview
This repository contains implementations of various Natural Language Processing (NLP) tasks. The assignments cover foundational techniques like tokenization, stemming, lemmatization, text representation (BoW, TF-IDF, Word2Vec), text cleaning, transformer models, morphology analysis, sentiment analysis, and N-gram-based auto-complete systems.

---

## Assignment List

### 1. *Tokenization & Stemming/Lemmatization*
   - Implement tokenization using:
     - Whitespace
     - Punctuation-based
     - Treebank
     - Tweet
     - Multi-Word Expression (MWE)
   - Apply stemming with *Porter Stemmer* and *Snowball Stemmer*.
   - Perform lemmatization using WordNetLemmatizer (NLTK).

### 2. *Text Representation: BoW, TF-IDF, Word2Vec*
   - *Bag-of-Words (BoW)*:
     - Count occurrences
     - Normalized count occurrences
   - Compute *TF-IDF* scores for the corpus.
   - Generate word embeddings using *Word2Vec*.

### 3. *Text Preprocessing & TF-IDF Pipeline*
   - Clean text (lowercasing, regex, etc.).
   - Lemmatize tokens and remove stopwords.
   - Perform label encoding on categorical data.
   - Create TF-IDF representations and save outputs (e.g., CSV, pickle).

### 4. *Transformer from Scratch (PyTorch)*
   - Build a transformer model with:
     - Multi-head self-attention
     - Positional encoding
     - Feed-forward layers
   - Train on a toy dataset (e.g., text generation).

### 5. *Morphology Analysis with Add-Delete Tables*
   - Study morphological processes (affixation, deletion, etc.).
   - Create add-delete tables to analyze word formation rules.
   - Test on example words (e.g., "happiness" → "happy" + "-ness").

### 6. *Advanced Sentiment Analysis Model*
   - Use state-of-the-art models like *BERT, **XLNet, or **RoBERTa*.
   - Fine-tune on a sentiment dataset (e.g., IMDb reviews).
   - Evaluate performance using accuracy/F1-score.

### 7. *N-gram Auto-Complete Algorithm*
   - Build an N-gram language model (bigram/trigram).
   - Implement smoothing techniques (Laplace, Kneser-Ney).
   - Generate context-aware suggestions for partial sentences.
