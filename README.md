# Traditional RAG with LangChain, FAISS, and ChatGroq

## Overview
This repository implements a **Retrieval-Augmented Generation (RAG)** system using:
- **LangChain** for orchestration
- **FAISS** as the vector store
- **OpenAIEmbeddings** for text embedding
- **ChatGroq** as the LLM model  

The system retrieves relevant context from a document store and enhances LLM responses with factual grounding.

## Features
✅ **Document Embedding** – Uses OpenAIEmbeddings to convert text into vector representations  
✅ **Efficient Retrieval** – FAISS enables fast similarity searches  
✅ **LLM-powered Responses** – ChatGroq generates answers based on retrieved context  
✅ **Pipeline Integration** – LangChain manages the flow between retrieval and generation  

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/apshuk21/traditional-RAG-projects.git
cd traditional-RAG-projects
pip install -r requirements.txt
