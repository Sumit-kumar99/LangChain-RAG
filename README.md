# 🧠 LangChain-RAG

This project demonstrates a simple but powerful **Retrieval-Augmented Generation (RAG)** system using **LangChain**, **HuggingFace Transformers**, and **FAISS**, designed to run entirely inside **Google Colab**.

Users can upload any `.txt` document and interact with it using natural language questions. The system retrieves relevant context and generates accurate, human-like answers using open-source models — **no API keys or paid services required**.

---

## 🚀 Features

- 📄 Upload any `.txt` file and process it in Colab  
- ❓ Ask natural-language questions about the content  
- 🔓 Uses free, open-source models (no OpenAI key needed)  
- 🧮 Embedding and retrieval handled locally using FAISS  
- 🧱 Built using LangChain’s modular RAG components  
- 🐣 Simple and beginner-friendly — ideal for learning LangChain  

---

## 📚 Use Case Examples

You can upload documents like:

- ✅ HR Policies  
- ✅ Meeting Notes  
- ✅ Terms and Conditions  
- ✅ Project Documentation  

Then ask questions such as:

- *“How many leave days are mentioned?”*  
- *“What are the working hours?”*  
- *“When are performance reviews held?”*  

---

## 🧠 How It Works

1. The uploaded text is split into smaller overlapping chunks  
2. These chunks are converted into vector embeddings using Sentence Transformers  
3. A FAISS vector store is created for fast similarity search  
4. When you ask a question, the top relevant chunks are retrieved  
5. A HuggingFace LLM (like `flan-t5-base`) generates a context-aware answer  

---

## 🛠️ Technologies Used

- **LangChain** – Orchestrates retrieval and generation logic  
- **FAISS** – High-performance vector similarity search  
- **SentenceTransformers** – For converting text to dense embeddings  
- **HuggingFace Transformers** – Provides the language model (LLM)  
- **Google Colab** – Cloud-based interactive Python runtime  

---

## 📦 Ideal For

- 👩‍🎓 Students and researchers exploring RAG-based NLP  
- 💬 Developers building document QA or chatbot tools  
- 🧪 Beginners experimenting with LangChain (offline or open-source)  
- 🔒 Users who want a no-cost, no-API-key solution  

---

## 🧰 Folder Contents

- `LangChain_RAG_Colab.ipynb` – Main Colab notebook  
- `example_file.txt` – Sample file for testing  
- `README.md` – This project overview  

---

## 👤 Author

**Sumit Kumar**  
Pull requests and contributions are welcome!
