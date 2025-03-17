# Medbot_vectorizedDatasetWithLLMS
This project involves creating a vectorized medical dataset by leveraging LLMs (Large Language Models) and medical books in PDF format. The medical texts were processed, converted into embeddings, and stored in a vector database for efficient retrieval. This enables semantic search and context-aware responses, making it useful for applications
Here's a concise **README** file for your **vectorized medical data project**:  

---

## 📚 Vectorized Medical Data  

This project processes **medical books (PDFs)** using **LLMs (Large Language Models)** to generate a **vectorized medical dataset**. The extracted text is converted into **embeddings** and stored in a **vector database**, enabling **semantic search** and **context-aware retrieval** of medical knowledge.  

### 🚀 Features  
- **Efficient Retrieval** – Enables fast, context-aware medical queries.  
- **Semantic Search** – Finds relevant information beyond keyword matching.  
- **Scalable Storage** – Stores embeddings in a vector database for real-time access.  
- **AI-Powered** – Uses **LLMs** for intelligent medical text processing.  

### 🛠️ Tech Stack  
- **LLMs (Large Language Models)**  
- **FAISS / Pinecone / ChromaDB** (Vector Database)  
- **Python (LangChain, Sentence Transformers)**  
- **PDF Processing (PyMuPDF, PDFMiner, PyPDF2)**  

### 🔧 Setup Instructions  
1. Install dependencies:  
   ```bash
   pip install langchain sentence-transformers faiss-cpu pymupdf
   ```  
2. Process medical PDFs and generate vector embeddings:  
   ```python
   from langchain.text_splitter import RecursiveCharacterTextSplitter
   from langchain.embeddings import OpenAIEmbeddings
   from langchain.vectorstores import FAISS  
   ```  
3. Store embeddings and perform **semantic search** for queries.  

### 📌 Use Cases  
✔️ Medical chatbots  
✔️ AI-driven medical research  
✔️ Clinical decision support  

### 🤝 Contributing  
Contributions are welcome! Feel free to submit **issues** or **pull requests**.  

---

