# LLM-Powered Fancam Analytics

An end-to-end AI analytics project integrating **Data Analytics**, **LLM-based Knowledge Construction**, **Hybrid Retrieval- RAG**, and an **AI Agent** for natural language analysis of K-pop fancam data.

---

## Project Overview

This project explores the factors influencing K-pop fancam views by combining statistical modeling with LLM applications.

The complete pipeline consists of three stages:

- **Data Analytics** – Identify key factors affecting fancam views through statistical modeling.
- **LLM Labeling** – Convert unstructured YouTube comments into a structured knowledge base.
- **Hybrid RAG + AI Agent** – Enable natural language analytics through automatic query routing and hybrid retrieval.

>  **Project Architecture**

<img width="1200" height="2460" alt="LLM-Powered Fancam Analytics architecture" src="https://github.com/user-attachments/assets/99799cf9-2c73-4309-b087-f2d386aeeee5" />

>  **AI Agent Workflow**

## AI Agent Workflow
                        User Query
                             │
                             ▼
                       Query Parser
                             │
               ┌─────────────┴─────────────┐
               │                           │
               ▼                           ▼
      Structured Query             Semantic Query
               │                           │
               ▼                           ▼
      Pandas Analytics           Metadata Filtering
                                               │
                                      Candidate Found?
                                         │         │
                                       Yes         No
                                         │         │
                                         ▼         ▼
                                 Hybrid Retrieval  Pure Vector Search
                                         │
                                         ▼
                                 Response Generator
                                         │
                                         ▼
                              Natural Language Answer
---

## Key Features

-  Statistical modeling for fancam view analysis
-  LLM-powered topic and sentiment annotation
-  Hybrid Retrieval combining Metadata Filtering and FAISS Vector Search
-  AI Agent with automatic query routing
-  Natural language interaction over structured and semantic knowledge

---

## Repository Structure

LLM-Powered-Fancam-Analytics/
│
├── notebooks/
│   ├── 01_Data_Analytics.ipynb
│   ├── 02_LLM_Labeling.ipynb
│   └── 03_AI_Agent_with_Hybrid_RAG.ipynb
│
├── src/
│   └── hybrid_rag_agent.py
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore

---

## Notebooks

###  01_Data_Analytics

Analyze stage-related features influencing fancam views through feature engineering, statistical modeling, and machine learning evaluation.

###  02_LLM_Labeling

Construct a structured knowledge base by rewriting YouTube comments and labeling discussion topics and sentiment using LLM.

###  03_Hybrid_RAG_AI_Agent

Build a Hybrid RAG system integrating metadata filtering, semantic retrieval, structured analytics, and an AI Agent for natural language question answering.

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
- Enhance retrieval with reranking techniques.
- Expand the knowledge base to additional K-pop datasets.
- Build an interactive visualization dashboard.

---

## Author

**Shu-An Chen**

Department of Statistics  
National Chengchi University
