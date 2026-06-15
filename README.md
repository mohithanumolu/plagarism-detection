# Plagiarism Detection  

## Overview  
This project detects plagiarism between text documents using **Natural Language Processing (NLP)** techniques. It compares documents by calculating similarity scores with methods like **TF‑IDF vectorization** and **cosine similarity**.  

## Dataset  
- Input: Sample text files provided in the repository  
- Task: Compare documents and flag plagiarism based on similarity threshold  

## Methodology  
- **Preprocessing**: Tokenization, stopword removal, vectorization  
- **Feature Extraction**: TF‑IDF representation of text  
- **Similarity Measure**: Cosine similarity between document vectors  
- **Decision Rule**: If similarity > threshold → plagiarism detected  

## Installation  
```bash
pip install -r requirements.txt
