# Document Retrieval System

## Overview

This project implements a document retrieval system using various search methods to find the most relevant documents based on a user query. The system integrates semantic search, hybrid search, FAISS (Facebook AI Similarity Search) with different configurations, and TF-IDF (Term Frequency-Inverse Document Frequency) with weighted scoring. 

## Features

- **Semantic Search**: Uses natural language processing to find relevant documents based on semantic meaning.
- **Hybrid Search**: Combines different search methods for improved results.
- **FAISS Search**: Provides efficient similarity search with different configurations (`nlist`, `nprobe`).
- **TF-IDF Search**: Incorporates TF-IDF scoring to rank documents by their relevance.
- **FAISS with TF-IDF**: Enhances search accuracy by combining FAISS and TF-IDF metrics with optional weight adjustments.
  
## Configuration

- **FAISS Configuration**: Adjust `nlist` and `nprobe` parameters to control search accuracy and performance.
- **TF-IDF Weights**: Customize weights for TF-IDF and FAISS to balance the influence of each metric.

## Contact

For any questions or feedback, please contact [breued1@gmail.com](mailto:your-email@example.com).
