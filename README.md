# Information Retrieval Notebook

This notebook demonstrates a basic information retrieval system using techniques like:

- **Preprocessing:** Tokenization, stemming, stop word removal
- **Inverted Index:** Building an inverted index for efficient term lookup
- **TF-IDF:** Calculating TF-IDF scores for documents and queries
- **Cosine Similarity:** Ranking documents based on cosine similarity with the query
- **Sentence BERT:** Utilizing Sentence BERT for semantic search


## Contents

1. **Step 1: Preprocessing Document**
   - Tokenizes, stems, and removes stop words from input text.

2. **Step 2: Building an Inverted Index**
   - Constructs an inverted index mapping terms to the documents containing them and their frequency.

3. **Step 3: Computing TF-IDF Scores**
   - Calculates TF-IDF scores for documents using scikit-learn.

4. **Step 4: Query Processing and Ranking**
   - Processes a user query, calculates its TF-IDF vector, and ranks documents based on cosine similarity with the query.

5. **Semantic Search using Sentence BERT**
   - Uses Sentence BERT to generate embeddings for documents and queries, then ranks documents based on cosine similarity between the embeddings.

## How to Run

1. Ensure you have the required libraries installed:
   
