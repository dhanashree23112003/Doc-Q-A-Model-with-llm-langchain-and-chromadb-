Project Title: Document Question Answering System
Project Overview
This project demonstrates how to build a basic document question answering system using Python and several key libraries:

Langchain: For creating question-answering pipelines.
Hugging Face Transformers: For generating embeddings.
ChromaDB: For storing and retrieving embeddings.
Groq Chat: For the language model.

Key Components
Document Loading and Preprocessing: Loads documents and splits them into smaller chunks.
Embedding Creation: Converts text chunks into numerical representations using Hugging Face Transformers.
Vector Database: Stores embeddings in a ChromaDB for efficient retrieval.
Language Model: Employs a Groq Chat language model for generating answers.
Question Answering Chain: Combines the above components to create a question-answering pipeline.
