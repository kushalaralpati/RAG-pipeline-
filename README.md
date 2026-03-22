# RAG-pipeline-📌 Project Title

Design and Evaluation of Retrieval-Augmented Generation (RAG) for Product Discovery in E-Commerce

📖 Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline to improve product discovery in e-commerce platforms.

Traditional search systems rely on keyword matching, which often fails to understand user intent. This project combines:

Keyword-based retrieval (BM25)
Semantic retrieval (FAISS + embeddings)
Generative AI (GPT-2)

to produce context-aware and meaningful product recommendations.

🚀 Features
🔍 Keyword-based search using BM25
🧠 Semantic search using SentenceTransformers + FAISS
🤖 Natural language generation using GPT-2
📊 Evaluation using Precision@k, Recall@k, and Latency
🛒 Real-world dataset (Amazon Reviews 2023)
🏗️ System Architecture

The pipeline consists of the following steps:

Data Loading
Amazon product reviews dataset
Preprocessing
Combine title + description + review text
Retrieval Module
BM25 (keyword search)
FAISS (semantic search)
Generation Module
GPT-2 generates recommendations
Evaluation
Precision@k
Recall@k
Latency
