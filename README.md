
# 🤖 RAG-Based LLM AI Chatbot

![RAG Based LLM AI Chatbot](sct.png)

**RAG-Based LLM AI Chatbot** is a powerful Streamlit-based application designed to simplify document management and interaction. Upload your PDF documents, generate embeddings for efficient retrieval, and interact intelligently with your documents through a locally hosted chatbot interface.

---

## 🚀 Key Features

* 📂 **Document Upload**
  Upload and preview your PDF files seamlessly within the app.

* 🧠 **Embedding Creation**
  Generate semantic embeddings for your documents to enable efficient search and retrieval.

* 🤖 **Chat with Documents**
  Leverage RAG (Retrieval-Augmented Generation) to interact with your documents using a smart chatbot powered by a local LLM.

* 💡 **User-Friendly Interface**
  Enjoy a sleek, emoji-enhanced, and responsive UI powered by Streamlit.

* 📬 **Developer Contact & Open Source Contribution**
  Connect with the developer or contribute to the project on GitHub.

---

## 🖥️ Tech Stack

| Component                                                                    | Description                                                                                     |
| ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **[LangChain](https://langchain.readthedocs.io/)**                           | Framework to orchestrate embedding creation, vector store operations, and chatbot interactions. |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)**          | Tool for robust PDF parsing and text extraction.                                                |
| **[BGE Embeddings (HuggingFace)](https://huggingface.co/BAAI/bge-small-en)** | High-quality sentence embeddings for semantic document representation.                          |
| **[Qdrant](https://qdrant.tech/)**                                           | Local vector database (via Docker) for storing and querying embeddings.                         |
| **[LLaMA 3.2 via Ollama](https://ollama.com/)**                              | Local large language model for generating intelligent, context-aware responses.                 |
| **[Streamlit](https://streamlit.io/)**                                       | Frontend framework for building the interactive chatbot UI.                                     |

---

## 📁 Directory Structure

```
document_buddy_app/
├── logo.png
├── new.py            # Main Streamlit app
├── vectors.py        # Embedding generation & Qdrant interaction
├── chatbot.py        # Chatbot logic with LLM and embeddings
├── requirements.txt  # List of dependencies
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Muskaanng/LLM_chatbot
cd RAG-Based-LLM-Chatbot
```

### 2. Set Up a Virtual Environment

**Option 1: Using `venv`**

* On Windows:

  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```
* On macOS/Linux:

  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

**Option 2: Using Anaconda**

```bash
conda create --name chatbot python=3.10
conda activate chatbot
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run new.py
```

Open your browser and go to the URL shown in the terminal (usually `http://localhost:8501`).

---

## 🤝 Contributing

We welcome all contributions!

### Steps to Contribute:

1. **Fork the Repository**
2. **Clone Your Fork**
3. **Create a Feature Branch**

   ```bash
   git checkout -b feature/YourFeatureName
   ```
4. **Make and Commit Your Changes**

   ```bash
   git commit -m "Add: Description of your feature"
   ```
5. **Push Your Branch**

   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Submit a Pull Request**

---

## 🔗 Useful Links

* [Streamlit Docs](https://docs.streamlit.io/)
* [LangChain Docs](https://langchain.readthedocs.io/)
* [Qdrant Docs](https://qdrant.tech/documentation/)
* [Ollama Integration Guide](https://github.com/langchain-ai/langchain-llms#ollama)

---

## 🪪 License

Distributed under the MIT License. See `LICENSE` for more details.

---

