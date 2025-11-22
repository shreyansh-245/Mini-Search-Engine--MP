# Simple-Search-Engine
The Simple Search Engine is a lightweight yet effective application designed to perform fast and accurate text-based searches. It enables users to search within a collection of documents and retrieve the most relevant results using the Vector Space Model (VSM) — a foundational technique in Natural Language Processing (NLP) that transforms text into numerical vectors in a multi-dimensional space.

Overview

This project demonstrates how to build a basic search engine from scratch using VSM for information retrieval. It systematically processes text data, represents it mathematically, and identifies documents closely related to a given user query through cosine similarity.

Project Workflow
Step 0 — Load the Corpus

Text documents stored locally are imported into the project environment. The NLTK library is used in later stages for linguistic processing.

Step 1 — Preprocessing & Tokenization

The text is cleaned and normalized by:

Tokenizing content

Lemmatizing words

Removing stop words
This ensures simplified and meaningful representation for analysis.

Step 2 — Dataset Creation

The processed text data is compiled and stored in a CSV file, forming a structured dataset.

Step 3 — Matrix Construction

A term-document matrix is generated to represent how frequently each term appears in each document.

Step 4 — Cosine Similarity Calculation

Cosine similarity is applied to measure how closely the query matches each document. The documents are then ranked based on similarity scores.

Usage Instructions

Clone the repository.

Install required dependencies (NLTK, Pandas).

Execute the main Python script to build and run the search engine.

Dependencies

NLTK

Pandas

Author

Shreyansh Gupta
