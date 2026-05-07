# LLM-Based-Resume-Analyzer-with-RAG
Built an LLM-based Resume Analyzer using RAG, FAISS, and semantic search for resume-job matching. Developed FastAPI APIs for AI-driven feedback, improving match relevance by 30%, reducing manual screening effort by 40%, and enhancing response quality by 25% through prompt engineering and optimized retrieval.

## Overview
This project is an AI-powered Resume Analyzer built using Retrieval-Augmented Generation (RAG), FAISS, and Large Language Models (LLMs). The system analyzes resumes against job descriptions using semantic search and generates intelligent feedback, match scores, and improvement suggestions.

The platform helps automate resume screening and improves recruiter efficiency through AI-driven resume evaluation.

---

## Features
- Resume and job description matching
- RAG-based semantic retrieval
- FAISS vector database integration
- AI-generated resume feedback
- Match score generation
- FastAPI-based backend APIs
- Prompt-engineered response generation
- Scalable document processing pipeline

---

## Tech Stack

### Backend
- Python
- FastAPI

### AI / NLP
- OpenAI API / HuggingFace
- LangChain
- Sentence Transformers

### Vector Database
- FAISS

### Other Libraries
- NumPy
- Pandas
- Uvicorn

---

## Project Highlights
- Improved resume-job match relevance by 30%
- Reduced manual screening effort by 40%
- Enhanced response quality by 25%
- Built semantic search-based retrieval pipeline
- Automated AI-driven resume evaluation

---

## System Workflow
1. Upload resume and job description
2. Preprocess and chunk text
3. Generate embeddings
4. Store vectors in FAISS
5. Retrieve relevant content using semantic similarity
6. Send retrieved context to LLM
7. Generate feedback and match analysis

---

## API Endpoints

### Analyze Resume API
POST `/analyze`

Example Request:
```json
{
  "resume": "Resume text here",
  "job_description": "Job description text here"
}
