# Movie-Shazam

Project Overview

This project is a content-based movie recommendation system that helps users identify movies based on short textual descriptions of their plots. The system functions similarly to "Shazam for movies," where users input descriptions (short, medium, or long), and the model retrieves the most relevant movie titles.

Methodology

The project utilizes multiple Natural Language Processing (NLP) techniques to compute textual similarity between the user's input and movie plots stored in a dataset.

1. Dataset and Preprocessing

The dataset contains 34,886 movie descriptions scraped from Wikipedia.

Additional metadata, including IMDb ratings and vote counts, enriches the dataset.

Movie plot embeddings are precomputed for fast retrieval.

2. Text Embedding Techniques

The system compares user input with stored movie plots using the following methods:

TF-IDF: A simple term-frequency-based representation.

TF-IDF with Weighting: Enhances keyword significance using frequency-based adjustments.

TF-IDF with N-grams: Captures multi-word expressions to improve semantic similarity.

Word2Vec: A word-embedding model that encodes semantic meanings.

LLM-based Embeddings (FAISS): Uses a transformer model to generate high-quality sentence embeddings for fast retrieval using FAISS indexing
