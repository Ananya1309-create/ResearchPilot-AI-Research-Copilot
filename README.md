# ResearchPilot: AI Research Copilot

ResearchPilot is an end-to-end Retrieval-Augmented Generation (RAG) system designed to assist researchers in exploring and analyzing academic literature.

The system enables semantic question answering over research papers and automated comparison of multiple studies using vector search and large language models.

---

## Features

### Single-Paper Research Assistant
- Upload PDF research papers
- Extract and process academic text
- Ask natural language questions
- Generate context-aware answers

### Multi-Paper Comparison Engine
- Compare methodologies across papers
- Compare datasets used in studies
- Identify key contributions
- Analyze differences between approaches

### Semantic Retrieval
- Intelligent chunking of research documents
- Embedding generation using SentenceTransformers
- Vector similarity search using ChromaDB
- Top-k relevant context retrieval

### LLM-Powered Reasoning
- Gemini integration for natural language responses
- Retrieval-based prompting to reduce hallucinations

---

## System Architecture

PDF Research Papers
↓
Text Extraction (PyPDF)
↓
Chunking (LangChain)
↓
Embeddings (SentenceTransformers)
↓
ChromaDB Vector Store
↓
Semantic Retrieval
↓
Gemini
↓
Question Answering & Multi-Paper Comparison

---

## Tech Stack

- Python
- Gemini API
- ChromaDB
- SentenceTransformers
- LangChain
- PyPDF
- Google Colab

---

## Example Queries

Single Paper:
- What is the main contribution of this paper?
- What methodology did the authors use?
- What datasets were used?
- What limitations are discussed?

Multi-Paper:
- Compare the methodologies used in these papers.
- Compare the datasets across studies.
- Which paper achieved the best performance?
- What research gaps remain across these studies?

---

## Results

ResearchPilot successfully enables:

- Semantic understanding of academic literature
- Context-aware question answering
- Automated comparison of multiple research papers
- Efficient retrieval using vector databases

---

## Future Work

- Literature Review Generation
- Citation Export
- Streamlit Web Interface
- Research Gap Detection

---

## Author

Ananya Shukla
B.Tech Student | AI/ML Enthusiast
