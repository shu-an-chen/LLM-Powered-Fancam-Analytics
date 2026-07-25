# LLM-Powered Fancam Analytics

An end-to-end AI analytics project that combines **Data Analytics**, **LLM-based Knowledge Construction**, **Hybrid Retrieval-(RAG)**, and an **AI Agent** to analyze K-pop fancam performance through natural language interaction.

---

## Project Overview

This project investigates the factors influencing K-pop fancam view counts by integrating statistical modeling with Large Language Model (LLM) applications.

The workflow consists of three stages:

1. **Data Analytics** – Identify key factors affecting fancam views through statistical modeling.
2. **LLM Labeling** – Transform unstructured YouTube comments into a structured knowledge base using LLM.
3. **Hybrid RAG + AI Agent** – Support natural language queries through metadata filtering, semantic retrieval, and structured analytics.

> 📌 *Architecture Diagram will be added here.*

---

## Key Features

- 📊 Statistical modeling for fancam view prediction
- 🤖 LLM-based topic and sentiment labeling
- 🔎 Hybrid Retrieval combining Metadata Filtering and FAISS Vector Search
- 🧠 AI Agent with automatic query routing
- 💬 Natural language analytics over structured and unstructured data

---

## Repository Structure

```
LLM-Powered-Fancam-Analytics/
│
├── 01_Data_Analytics.ipynb
├── 02_LLM_Labeling.ipynb
├── 03_Hybrid_RAG_AI_Agent.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Notebooks

### 📘 01_Data_Analytics

Explores the relationship between stage-related features and fancam views using statistical models, including feature engineering, multiple regression, stepwise selection, Ridge Regression, and K-Fold Cross Validation.

---

### 📙 02_LLM_Labeling

Constructs a structured knowledge base by rewriting YouTube comments, labeling discussion topics and sentiment with LLM, and validating the generated annotations through statistical analysis.

---

### 📗 03_Hybrid_RAG_AI_Agent

Builds a Hybrid RAG system integrating metadata filtering, semantic retrieval, FAISS vector search, and an AI Agent capable of automatically routing user queries to structured analytics or semantic retrieval.

---

## Technology Stack

**Programming**

- Python

**Data Analysis**

- Pandas
- NumPy
- Scikit-learn
- Statsmodels

**LLM**

- OpenAI API
- Prompt Engineering
- Pydantic Structured Output

**Retrieval**

- OpenAI Embeddings
- FAISS
- Hybrid Retrieval
- Metadata Filtering

---

## Future Work

- Deploy the AI Agent as an interactive web application.
- Improve retrieval quality through reranking techniques.
- Expand the knowledge base with additional K-pop datasets.
- Integrate visualization dashboards for interactive analytics.

---

## Author

**Shu-An Chen**

Department of Statistics  
National Chengchi University
