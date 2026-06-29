# 🤖 Transformers & RAG Educational Assistant

An educational Natural Language Processing (NLP) project exploring Transformer models, the Hugging Face ecosystem, and Retrieval-Augmented Generation (RAG) through the implementation of an intelligent assistant capable of answering questions about Transformers and RAG systems.

---

## 📌 Overview

This project was developed as part of the **Natural Language Processing (NLP)** course.

The project explores:

- Transformer architectures
- Hugging Face library
- Transfer Learning
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)

An educational assistant was implemented to compare the capabilities of a standalone LLM with those of a RAG-based system using an external knowledge base.

---

## 🎯 Project Objectives

The project is divided into three main parts:

### 1. Hugging Face Exploration

- Installing the Transformers library
- Loading pre-trained models
- Using tokenizers
- Exploring Hugging Face pipelines
- Understanding Transfer Learning

---

### 2. NLP Applications

Implementation of several NLP tasks using pre-trained Transformer models:

- Text Classification
- Sentiment Analysis
- Question Answering
- Automatic Text Summarization

---

### 3. Implementation of a RAG System

A complete Retrieval-Augmented Generation pipeline was developed, including:

- Document collection
- Text extraction
- Corpus cleaning
- Chunk generation
- Embedding generation
- Vector database construction using FAISS
- Semantic retrieval
- Prompt augmentation
- Answer generation using a Large Language Model

---

## 📚 Knowledge Base

The knowledge base was built using several academic references, including:

- Attention Is All You Need (Vaswani et al., 2017)
- Natural Language Processing with Transformers
- Stanford Speech and Language Processing (Transformers)
- Stanford Speech and Language Processing (RAG)
- Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks
- Sentence-BERT
- FAISS

---

## ⚙️ Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Sentence Transformers
- FAISS
- NumPy
- Regular Expressions

---

## 📂 Repository Structure

```text
Transformers-RAG-Educational-Assistant/
│
├── notebook/
│   └── projetNLP.ipynb
│
├── report/
│   └── NLP_Report.pdf
│
├── README.md
│
└── LICENSE
```

---

## 🧠 Methodology

### Part I — Standalone LLM

- Install the required libraries
- Load the FLAN-T5 pre-trained model
- Generate answers to several questions
- Analyze the limitations of using a standalone LLM

---

### Part II — RAG System

- Build a document knowledge base
- Extract and clean textual data
- Split documents into chunks
- Generate embeddings using Sentence Transformers
- Build a FAISS vector database
- Retrieve the most relevant chunks
- Construct an augmented prompt
- Generate the final answer using FLAN-T5

---

### Part III — Experimental Comparison

The same questions were asked to:

- FLAN-T5 (LLM only)
- FLAN-T5 + RAG

The obtained results demonstrate the impact of external knowledge on the quality of generated responses.

---

## ✅ Results

The experiments show that:

- Hugging Face greatly simplifies the use of Transformer models.
- Transfer Learning enables the reuse of powerful pre-trained models.
- A standalone LLM provides general knowledge but may produce incomplete or ambiguous answers.
- Integrating a RAG system significantly improves the relevance, richness, and accuracy of generated responses by leveraging external documents.

---

## 📄 Project Files

- 📓 Google Colab Notebook
- 📑 Project Report (PDF)

---

## 👩‍💻 Author

**Douae Laayouni**

Engineering Student in Data Engineering

Interested in:

- Natural Language Processing
- Large Language Models
- Retrieval-Augmented Generation
- Artificial Intelligence
