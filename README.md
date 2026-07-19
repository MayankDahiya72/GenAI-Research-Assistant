# GenAI-Research-Assistant
# 📚 AI Research Paper Intelligence System

An end-to-end **Generative AI** application that enables intelligent exploration of scientific research papers using **Semantic Search**, **Retrieval-Augmented Generation (RAG)**, **Large Language Models (LLMs)**, and **Natural Language Processing (NLP)**.

The system allows users to search research papers semantically, retrieve the most relevant publications, generate concise summaries, extract keywords and named entities, recommend similar papers, and answer research questions using modern Generative AI techniques.

---

## 🚀 Features

* 🔍 Semantic Search using Sentence Transformers
* 📑 Vector Search with FAISS
* 🤖 Retrieval-Augmented Generation (RAG)
* 💬 AI-powered Research Question Answering using Llama 3.1 (Groq)
* 📝 Research Paper Summarization using BART
* 🏷 Keyword Extraction using KeyBERT
* 🧠 Hybrid Named Entity Recognition (spaCy + Regex + LLM)
* 📚 Research Paper Recommendation System
* 📊 Research Paper Category Classification
* 📈 Document Clustering using K-Means and PCA Visualization

---

# 🏗 Project Workflow

```
Research Papers
       │
       ▼
Data Cleaning & Preprocessing
       │
       ▼
Sentence Transformer Embeddings
       │
       ▼
FAISS Vector Database
       │
       ├──────────────┐
       ▼              ▼
Semantic Search   Paper Recommendation
       │
       ▼
Retrieved Research Papers
       │
       ▼
Llama 3.1 + LangChain (RAG)
       │
       ▼
Generated Answers
       │
       ├───────────────┐
       ▼               ▼
Summarization     Entity & Keyword Extraction
```

---

# 🛠 Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Scikit-learn
* Sentence Transformers
* FAISS
* LangChain
* LangChain-Groq
* Hugging Face Transformers
* spaCy
* KeyBERT
* Matplotlib

### Models Used

* all-MiniLM-L6-v2 (Sentence Transformers)
* Llama 3.1 8B Instant (Groq)
* facebook/bart-large-cnn
* SGD Classifier
* K-Means Clustering

---

# 📂 Dataset

This project uses the **arXiv Scientific Research Papers Dataset**.

You can download the dataset from Kaggle:

**https://www.kaggle.com/datasets/Cornell-University/arxiv**

After downloading, place the CSV file in the project directory:

```
arXiv_scientific_dataset.csv
```

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-Research-Paper-Intelligence-System.git
```

Move into the project

```bash
cd AI-Research-Paper-Intelligence-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a file named

```
.env
```

Add your Groq API key

```
GROQ_API_KEY=your_api_key_here
```

---

# ▶ Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
AI_Research_Paper_Intelligence_System.ipynb
```

Run all cells sequentially.

---

# 📌 Project Modules

### Data Preprocessing

* Data Cleaning
* Duplicate Removal
* Missing Value Handling
* Text Preprocessing

---

### Semantic Search

* Sentence Embeddings
* FAISS Vector Search
* Top-K Similar Research Papers

---

### Research Paper Recommendation

* Similar Paper Retrieval
* Embedding Similarity Search

---

### Research Paper Classification

* Label Encoding
* SGD Classifier
* Classification Report
* Confusion Matrix

---

### Document Clustering

* K-Means Clustering
* PCA Visualization

---

### Keyword Extraction

* KeyBERT

---

### Named Entity Recognition

* spaCy
* Regex Rules
* LLM-assisted Hybrid NER

---

### Research Paper Summarization

* Facebook BART Large CNN

---

### Retrieval-Augmented Generation (RAG)

* LangChain
* Groq
* Llama 3.1
* Context Retrieval
* AI-powered Question Answering

---

### AI Research Agent

The intelligent research agent can:

* Retrieve relevant research papers
* Recommend similar papers
* Extract keywords
* Extract named entities
* Generate summaries
* Answer user research queries using retrieved context

---

# 📊 Results

The system successfully demonstrates:

* Semantic retrieval of research papers
* High-quality vector search
* AI-powered question answering
* Automatic paper summarization
* Research paper recommendation
* Keyword extraction
* Named Entity Recognition
* Research paper clustering
* Research paper classification

---

# 🔮 Future Improvements

* Web-based user interface
* Multi-document summarization
* Citation generation
* PDF upload and processing
* Conversation memory
* Multi-LLM support
* Research trend visualization
* Streamlit/FastAPI deployment
* Docker support
* Cloud deployment


