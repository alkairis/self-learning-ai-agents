# Self-Learning AI Agents for Knowledge Management  

## **Overview**  
This project builds an **Agentic AI** system for knowledge management. It autonomously learns, retrieves, and refines knowledge using a multi-agent architecture. The system can handle structured and unstructured data, improving its responses over time.  

## **Features**  
- **Autonomous Learning** – Continuously updates knowledge from various sources.  
- **Multi-Agent System** – Includes retrieval, refinement, and reasoning agents.  
- **Memory & Context Awareness** – Tracks past interactions for better responses.  
- **Hybrid Retrieval** – Uses **local embeddings** and **Pinecone vector search**.  
- **FastAPI API** – For interacting with AI agents.  
- **LLM Integration** – Uses **Groq API** and **Hugging Face models**.  

## **Tech Stack**  
- **Python**  
- **Llama Index** (for retrieval & indexing)  
- **FastAPI** (backend API)  
- **Hugging Face** (LLMs)  
- **Groq API** (for efficient query processing)  
- **Pinecone** (vector database)  
- **Local Embeddings** (for lightweight retrieval)  

## **Architecture**  
1. **Data Ingestion** – Parses PDFs, text, and API data into a knowledge base.  
2. **Embeddings & Storage** – Stores embeddings locally and in Pinecone for retrieval.  
3. **Agent Workflow**  
   - **Retrieval Agent** – Fetches relevant information.  
   - **Refinement Agent** – Enhances retrieved content.  
   - **Reasoning Agent** – Provides context-aware responses.  
4. **LLM Processing** – Uses Groq API & Hugging Face models for query responses.  
5. **User Interface** – Can be a **CLI tool or Streamlit-based UI**.  

## **Installation**  
```bash
git clone https://github.com/alkairis/self-learning-ai-agents.git
cd self-learning-ai-agents
python -m venv venv
source venv/scripts/activate
pip install poetry
poetry install
```
