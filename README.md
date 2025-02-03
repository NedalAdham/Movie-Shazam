# 🎬 Movie Shazam

## 📌 Overview
This project develops a content-based movie Retrival system that retrieves movies based on user-provided plot descriptions. The system leverages multiple NLP techniques to improve accuracy and relevance.
### 1️⃣ TF-IDF & Variants  
- **Standard TF-IDF**: Computes cosine similarity between user input and movie plots.  
- **Weighted TF-IDF**: Incorporates IMDb ratings and vote counts for better ranking.  
- **TF-IDF with N-grams**: Uses unigrams, bigrams, and trigrams for improved phrase matching.
### 2️⃣ LLM-Based Embeddings  
- Uses transformer-based models (e.g., `sentence-transformers/all-mpnet-base-v2`) to generate high-quality semantic embeddings.  
### 3️⃣ Word2Vec Model  

## 📊 Evaluation
The system is tested with different input lengths (long, mid, short) to measure retrieval accuracy, comparing results across different techniques.
