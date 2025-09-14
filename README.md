# ProductSearch-AI Assistant

### AI-Powered Product Search & Q&A with Retrieval-Augmented Generation (RAG)

**ProdSearch-RAG** is an end-to-end system that enables users to **search products** and **ask natural language questions** about them.  
It integrates **OpenAI Large Language Models (GPT-3.5 & GPT-4)** with a **vector database (Pinecone)** to provide **semantic product search** and **context-grounded answers**.

The pipeline automates **web scraping**, **preprocessing**, and **embedding creation**, stores embeddings in Pinecone, and retrieves relevant context for **LLM-powered answers**.  
A **Streamlit UI** allows users to explore products conversationally, making product discovery more natural and intuitive.

---

## Problem Statement

Traditional product search is **keyword-based**, which often fails for natural language queries like:
- *“Which Sony headphones are best for noise cancellation under $200?”*
- *“What’s the difference between Sony WH-1000XM4 and XM5?”*

This project solves the problem by combining **semantic retrieval** with **LLMs**, enabling **intelligent product search and Q&A**.

---

## Features

- **Product Search** – Retrieve items by price, specifications, or features
- **Q&A with LLMs** – Answer product-related questions using **OpenAI GPT models**
- **Web Scraping** – Automated collection of product data (price, EMI, specs)
- **Preprocessing** – Cleans and tokenizes text for embedding efficiency
- **Semantic Retrieval** – Stores and queries embeddings in **Pinecone**
- **RAG Pipeline** – Combines **retrieval + generation** for accurate, context-based results
- **Streamlit UI** – Interactive interface for product search and Q&A
- **Evaluation** – Includes unit tests and prompt-based accuracy checks

---

## Tech Stack

- **Programming**: Python (Selenium, BeautifulSoup, NLTK, Streamlit)
- **LLMs**: OpenAI GPT-3.5 & GPT-4
- **Vector Database**: Pinecone (FAISS compatible pattern)
- **Environment Management**: Conda, dotenv

---

##  Accomplishments

- Built a complete **RAG pipeline** from data collection to LLM-powered responses
- Enabled **natural language Q&A** for product catalogs using **OpenAI GPT models**
- Designed a **Streamlit UI** for intuitive product exploration
- Evaluated performance with **unit tests and prompt-based accuracy checks**
- Demonstrated real-world application of **LLMs, embeddings, and vector databases** in an **AI engineering project**

---
