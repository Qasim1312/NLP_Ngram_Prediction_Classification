# NLP_Ngram_Prediction_Classification


## Overview
This project focuses on **building N-Gram models (Unigram, Bigram, and Trigram)** for text prediction and then using these models for **movie review classification**.

## Dataset
The dataset used is the **IMDB Dataset** containing labeled movie reviews.

## Features Implemented
- **Text Prediction:** Predicts the next word based on Unigram, Bigram, and Trigram models.
- **Movie Review Classification:** Uses Bayesian classification with N-Gram models to label movie reviews as positive or negative.

## Implementation Details
1. **Data Preprocessing**
   - Tokenization & Lowercasing
   - Stopword Removal
   - Punctuation Removal

2. **N-Gram Model**
   - **Unigram Model:** Predicts the most frequent word.
   - **Bigram Model:** Predicts based on the previous word.
   - **Trigram Model:** Predicts based on the previous two words.

3. **Movie Review Classification**
   - Bayesian Classification based on N-Gram probability.
   - Labels reviews as **Positive or Negative**.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/NLP_Ngram_Prediction_Classification.git
   cd NLP_Ngram_Prediction_Classification

2. Install dependencies:
   pip install nltk pandas

3. Run the script:
   ngram_classification.py
