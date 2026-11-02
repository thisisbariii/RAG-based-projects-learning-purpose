# RAG-Based Projects & Learning

A collection of projects and experiments focused on learning **Retrieval-Augmented Generation (RAG)**, Large Language Models (LLMs), embeddings, vector databases, and AI-powered applications using Python.

The goal of this repository is to understand how LLMs can retrieve relevant information from external data sources and generate context-aware responses.

## Projects

### 1. YouTube Transcript RAG
- Extract transcripts from YouTube videos.
- Split transcripts into smaller chunks using Recursive Character Text Splitter.
- Generate embeddings using OpenAI Embeddings.
- Store and retrieve vectors using FAISS.
- Retrieve relevant context based on user queries.
- Generate answers using an LLM.

**Technologies:** Python, LangChain, OpenAI, FAISS, YouTube Transcript API.

## Tech Stack

- **Language:** Python
- **Framework:** LangChain
- **LLMs:** OpenAI, Groq
- **Embeddings:** OpenAI Embeddings (`text-embedding-3-small`)
- **Vector Database:** FAISS
- **Data Processing:** Recursive Character Text Splitter
- **Environment:** VS Code, Python Virtual Environment

## Project Structure

```text
rag_app/
│
├── youtube.ipynb
├── .env.example
├── .gitignore
└── README.md
```

## Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/thisisbariii/RAG-based-projects-learning-purpose.git
cd RAG-based-projects-learning-purpose
```

**2. Create a virtual environment**

```bash
python -m venv venv
```

**3. Activate the environment**

Windows:

```bash
venv\Scripts\activate
```

**4. Install dependencies**

```bash
pip install langchain langchain-openai langchain-community faiss-cpu python-dotenv youtube-transcript-api
```

**5. Configure environment variables**

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

Never commit your `.env` file or expose API keys in notebooks.

**6. Run the notebook**

```bash
jupyter notebook youtube.ipynb
```

## Learning Objectives

- Understanding Retrieval-Augmented Generation.
- Working with document loaders and text splitters.
- Understanding embeddings and semantic search.
- Building vector stores using FAISS.
- Connecting LLMs with external knowledge sources.
- Generating context-aware responses using retrieved information.

## Future Improvements

- PDF-based RAG applications.
- Conversational RAG with chat history.
- Retrieval evaluation and optimization.
- Advanced RAG techniques.
- Agentic RAG using LangGraph.

## Author

**Abdul Basha Shaikh**

- GitHub: [@thisisbariii](https://github.com/thisisbariii)

---

*This repository is maintained for learning, experimentation, and practical implementation of RAG-based AI applications.*
