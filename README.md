# 📚 AI Research Paper Intelligence System

An AI-powered research assistant that enables users to search, retrieve, summarize, compare, and analyze Machine Learning research papers using Semantic Search, Sentence Transformers, FAISS, LangChain, and Large Language Models.

---

## 🚀 Overview

Searching through thousands of research papers using traditional keyword-based methods is often inefficient. This project overcomes that limitation by leveraging semantic search, allowing users to retrieve papers based on meaning rather than exact keywords.

The system creates vector embeddings for research papers, stores them in a FAISS vector database, and retrieves the most relevant documents for a given query. It further enhances the results by generating concise summaries and extracting important keywords using AI.

---

## ✨ Features

- 🔍 Semantic search for research papers
- 🤖 AI-powered paper summarization
- 📚 Fast retrieval using FAISS Vector Database
- 🧠 Sentence Transformer embeddings
- 🏷️ Automatic keyword extraction with KeyBERT
- ⚖️ Research paper comparison
- 💬 Natural language query support
- 🔗 LangChain integration with Groq LLM
- 📄 Interactive notebook-based workflow

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Dataset | ML-ArXiv Papers Dataset |
| Embedding Model | all-MiniLM-L6-v2 |
| Vector Database | FAISS |
| Framework | LangChain |
| LLM | Groq (Llama 3.1 8B Instant) |
| NLP | Sentence Transformers |
| Keyword Extraction | KeyBERT |
| Development | Jupyter Notebook |

---

## 📂 Project Structure

```
AI-Research-Paper-Intelligence-System/
│
├── Coding_Blocks_Research_Paper_Intelligence_System.ipynb
├── README.md
├── requirements.txt
├── dataset.md
```

---

## ⚙️ Workflow

1. Load the ML-ArXiv Papers dataset from Hugging Face.
2. Extract paper titles and abstracts.
3. Preprocess the dataset.
4. Generate semantic embeddings using Sentence Transformers.
5. Store embeddings inside a FAISS Vector Database.
6. Accept a natural language research query.
7. Retrieve the most relevant papers.
8. Generate AI-powered summaries.
9. Extract important keywords.
10. Display meaningful research insights.

---

## 📊 Architecture

```
                   User Query
                        │
                        ▼
           Sentence Transformer
                        │
                        ▼
               Query Embedding
                        │
                        ▼
              FAISS Vector Search
                        │
                        ▼
         Top Relevant Research Papers
                        │
                        ▼
              LangChain + Groq LLM
          ┌─────────┬─────────┬─────────┐
          ▼         ▼         ▼
      Summary   Keywords   Comparison
          │
          ▼
     Final AI Response
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-Research-Paper-Intelligence-System.git

cd AI-Research-Paper-Intelligence-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install all required dependencies.
3. Configure your Groq API Key.
4. Run each notebook cell in sequence.
5. Enter your research topic or question.
6. View retrieved papers, summaries, and extracted keywords.

---

## 💡 Example Queries

- Transformer Models for NLP
- Explainable Artificial Intelligence
- Deep Learning for Medical Imaging
- Reinforcement Learning
- Computer Vision
- Federated Learning
- Graph Neural Networks
- AI in Healthcare

---

## 📚 Dataset

Dataset Source:

https://huggingface.co/datasets/CShorten/ML-ArXiv-Papers

Columns Used:
- Title
- Abstract

Preprocessing:
- Missing value handling
- Title and abstract merged into a single text field
- Sentence embeddings generated for semantic search

---

## 🎯 Future Enhancements

- Streamlit Web Interface
- Research Paper PDF Upload
- Citation Generation
- RAG-based Question Answering
- Interactive Dashboard
- Multi-Agent Research Assistant
- Research Report Generation (PDF)

---

## 📖 Learning Outcomes

This project demonstrates practical implementation of:

- Semantic Search
- Vector Databases
- Natural Language Processing
- Sentence Embeddings
- Large Language Models
- LangChain
- KeyBERT
- Retrieval-Augmented Generation (RAG)
- Information Retrieval Systems

---

## 📜 License

This project is intended for educational and research purposes only.

---

## 👩‍💻 Author

**Disha Kinge**
---

⭐ If you found this project useful, consider giving it a Star!
