# 🤖 AI PDF Chatbot – RAG Based Document Assistant

An intelligent AI-powered PDF chatbot built using **LangChain, LangGraph, Groq LLM, OpenAI Embeddings, and Streamlit**.
This application allows users to upload PDF documents and ask questions directly from the uploaded files using a Retrieval-Augmented Generation (RAG) pipeline.

---

# 🚀 Features

✅ Upload Multiple PDF Files
✅ Ask Questions from Uploaded Documents
✅ Retrieval-Augmented Generation (RAG)
✅ OpenAI Embeddings for Semantic Search
✅ LangGraph ReAct Agent Integration
✅ Groq Llama 3.3 Model Support
✅ Streamlit Chat Interface
✅ Conversation Memory Support
✅ Fast Vector Similarity Search

---

# 🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* LangGraph
* Groq API
* OpenAI Embeddings
* In-Memory Vector Store
* PyPDF Loader

---

# 📂 Project Structure

```bash
project/
│
├── app.py
├── requirements.txt
├── .env
├── doc_files/
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory and add:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

---

# 🧠 How It Works

1. User uploads PDF documents
2. PDFs are loaded and split into chunks
3. OpenAI Embeddings convert chunks into vectors
4. Vector Store performs similarity search
5. LangGraph ReAct Agent retrieves relevant context
6. Groq Llama Model generates accurate answers

---

# 📸 Demo

Upload PDFs and ask questions like:

* “Summarize this document”
* “What is the main topic?”
* “Explain chapter 2”
* “What are the key points?”

---

# 📦 Requirements

```txt
streamlit
langchain
langchain-community
langchain-openai
langchain-groq
langgraph
pypdf
python-dotenv
tiktoken
```

---

# 🔒 Important

Add `.env` to `.gitignore`

```gitignore
.env
__pycache__/
```

---

# 🌟 Future Improvements

* Persistent Vector Database (FAISS/ChromaDB)
* Chat History Storage
* Source Citations
* Multi-File Search
* Authentication System
* Docker Deployment

---

# 👨‍💻 Author

Naveed Ahmad

GitHub: https://github.com/naveed376

---

# ⭐ If You Like This Project

Give this repository a star ⭐ and share it with others.
