# Word2Vec-model-from-pdf
This project trains a word2vec model from PDF files, extracting and preprocessing text for semantic analysis. It uses PyMuPDF or pdfminer for PDF conversion and gensim for word embeddings. Applications include text similarity and document clustering, useful for NLP tasks like keyword extraction and content categorization.
# Features
PDF Text Extraction: Converts PDF documents to raw text using libraries like PyMuPDF or pdfminer.

Text Preprocessing: Cleans and tokenizes text, removes stop words, and applies stemming/lemmatization.

Word2Vec Model Training: Trains a word2vec model using gensim for semantic understanding.

Applications: Suitable for NLP tasks, including text similarity, keyword extraction, and document clustering.
# Requirements
Python 3.x

gensim, PyMuPDF (or pdfminer), nltk/spaCy for NLP preprocessing
