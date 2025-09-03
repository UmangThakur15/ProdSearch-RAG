## ProdSearch-RAG

### AI-Powered Product Search & Q&A with Retrieval-Augmented Generation (RAG)

ProdSearch-RAG is an end-to-end system that enables users to search products and ask questions in natural language. It integrates OpenAI Large Language Models (GPT-3.5 & GPT-4) with a vector database (Pinecone) to provide semantic product search and context-grounded answers.

The pipeline scrapes product catalogs, preprocesses and embeds descriptions, stores them in Pinecone, and retrieves context for OpenAI LLM-powered responses. A Streamlit UI lets users explore products conversationally, making product discovery more intuitive.
