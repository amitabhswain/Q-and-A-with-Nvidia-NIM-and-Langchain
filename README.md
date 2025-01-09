# Q&A application with Nvidia NIM and Langchain


This project demonstrates building a RAG (Retrieval Augmented Generation) application using Nvidia NIM (Neural Inference Microservices) and LangChain. The application allows users to perform document question-answering with the following key features:

**Core Components**

• Nvidia NIM for model inference and embeddings

• LangChain for RAG pipeline implementation

• Streamlit for the user interface

• PDF document processing capabilities

**Key Functionality**

• Document ingestion and processing from PDF files

• Vector embeddings generation using Nvidia embeddings

• Question-answering using Llama 2 70B model through Nvidia NIM
• Interactive chat interface with context display


**Technical Details**

• Uses recursive text splitting for document chunking
• Implements FAISS vector store for document retrieval
• Leverages Nvidia's API for fast model inference
• Includes session state management for vector storage

The project showcases Nvidia NIM's capabilities for enterprise-grade AI deployment while providing a practical implementation of a document QA system.
