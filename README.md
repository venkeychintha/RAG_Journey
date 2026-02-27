# 🧪 RAG Lab

A hands-on learning repository where I explored and implemented **Retrieval-Augmented Generation (RAG)** from the ground up using LangChain, covering everything from basic data ingestion to advanced RAG techniques.

---

## 🗺️ What I Explored

| Topic | Concepts Covered |
|---|---|
| 📥 Data Ingestion | Loading PDFs, DOCX, Excel, JSON, Wikipedia |
| 🔢 Vector Embeddings & Databases | HuggingFace embeddings, OpenAI embeddings, ChromaDB, FAISS |
| 🗄️ Vector Stores | Storing, persisting, and querying vector stores |
| ✂️ Advanced Chunking | Recursive, semantic, and document-aware chunking strategies |
| 🔍 Query Enhancement | Query rewriting, HyDE, multi-query retrieval |
| 🖼️ Multimodal RAG | Handling text + non-text documents |

---

## 🛠️ Tech Stack

- **Framework:** [LangChain](https://www.langchain.com/)
- **LLMs:** OpenAI, Groq
- **Embeddings:** HuggingFace (`sentence-transformers`), OpenAI
- **Vector Stores:** ChromaDB, FAISS
- **Document Loaders:** PyPDF, PyMuPDF, python-docx, unstructured, pandas
- **Package Manager:** [uv](https://github.com/astral-sh/uv)
- **Python:** 3.13+

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/rag-lab.git
cd rag-lab
```

### 2. Install `uv` (if not already installed)

```bash
pip install uv
```

### 3. Create virtual environment and install dependencies

```bash
uv venv
source .venv/bin/activate        # Mac/Linux
.venv\Scripts\activate           # Windows

uv pip install -r requirements.txt
```

### 4. Set up environment variables

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_key_here
GROQ_API_KEY=your_groq_key_here
HUGGINGFACEHUB_API_TOKEN=your_huggingface_token_here
```

> 🔑 Get your keys from [OpenAI](https://platform.openai.com/), [Groq](https://console.groq.com/), and [HuggingFace](https://huggingface.co/settings/tokens)

---

## 📁 Project Structure

```
rag-lab/
├── main.py                  # Entry point
├── requirements.txt         # Dependencies
├── pyproject.toml           # Project metadata (uv)
├── .env.example             # Sample env file (no real keys)
├── .gitignore
└── README.md
```

---

## 📦 Dependencies

```
langchain, langchain-community, langchain-core
langchain-openai, langchain-groq, langchain-huggingface
langchain-experimental
chromadb, faiss-cpu
sentence-transformers, tiktoken
pypdf, pymupdf, pdfminer
python-docx, docx2txt, unstructured[docx]
pandas, openpyxl, jq, matplotlib
rank_bm25, wikipedia
python-dotenv
```

---

## 🔐 Security Note

Never commit your `.env` file. It is listed in `.gitignore`. Use `.env.example` as a reference template instead.

---

## 📚 Learning Resources

- [LangChain Docs](https://docs.langchain.com/)
- [ChromaDB Docs](https://docs.trychroma.com/)
- [HuggingFace Models](https://huggingface.co/models)
- [Groq Console](https://console.groq.com/)
- [uv Docs](https://docs.astral.sh/uv/)

---

## 👤 Author

**Your Name**  
[GitHub](https://github.com/your-username) • [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📄 License

MIT License — feel free to use this as a reference for your own RAG learning journey!
