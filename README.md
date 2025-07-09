# LangChain-RAG

This project demonstrates a simple but powerful Retrieval-Augmented Generation (RAG) system using LangChain, HuggingFace Transformers, and FAISS, designed to run entirely inside Google Colab.

Users can upload any .txt document and interact with it using natural language questions. The system will retrieve relevant context and generate accurate, human-like answers using open-source models — no API keys or paid services required.

🚀 Features
Upload any .txt file and process it in Colab

Ask natural-language questions about the file

Uses free, open-source models (no OpenAI key needed)

Embedding and retrieval handled locally using FAISS

Built using LangChain’s modular RAG components

Simple and beginner-friendly — ideal for learning LangChain

📚 Use Case Example
You can upload documents like:

HR policies

Meeting notes

Terms and conditions

Project documentation

Then ask questions like:

“How many leave days are mentioned?”

“What are the working hours?”

“When are performance reviews held?”

🧠 How It Works
The uploaded text is split into smaller overlapping chunks.

These chunks are converted into numerical vectors using Sentence Transformers.

A FAISS vector store is built to allow fast similarity-based search.

When you ask a question, the system retrieves the most relevant chunks.

A HuggingFace LLM (like FLAN-T5) uses these chunks to generate an accurate answer.

🛠️ Technologies Used
LangChain: For chaining components (retriever + LLM)

FAISS: For fast vector similarity search

SentenceTransformers: For generating document embeddings

HuggingFace Transformers: For the question-answering language model

Google Colab: For a lightweight, cloud-based runtime

📦 Ideal For
Students and researchers exploring RAG concepts

Developers building document chatbots

Anyone wanting to experiment with LangChain without needing an OpenAI key

Those looking for an all-offline, free pipeline to query custom documents

🧰 Folder Contents
A Colab notebook that guides the entire flow interactively

Example .txt files to test

This README for project documentation


