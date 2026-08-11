# CareerLens

## Business Problem:

Finding the right job has become increasingly difficult for graduates and professionals. Many applicants receive little or no feedback after applying, making it challenging to understand whether their resume matches the role, which skills are missing, or how to improve their chances of getting shortlisted.

Current job portals focus primarily on listing vacancies rather than helping candidates identify skill gaps, optimize their resumes, and prepare effectively for interviews.

---

## What CareerLens Does
CareerLens is an AI-powered career platform designed to help job seekers improve their employability through intelligent career guidance.

The platform analyzes resumes, matches candidates with relevant job roles, identifies missing skills, explains why a resume is or isn't a good fit for a position, and provides personalized recommendations to strengthen applications. It also assists users with interview preparation and AI-powered career insights.

Status: 🚧 Currently under active development.

---

System Architecture

Resume
        │
        ▼
 Resume Parsing
        │
        ▼
 Resume Analysis
        │
        ├───────────────┐
        ▼               ▼
 Skill Gap        Job Matching
 Analysis          Engine
        │               │
        └──────┬────────┘
               ▼
       LLM Reasoning Layer
               │
               ▼
Personalized Recommendations
               │
               ▼
 Interview Preparation

---

## Tech Stack

### Backend

- FastAPI
- Python
- PostgreSQL
- pgvector
  
### AI
- Groq LLM
- LangChain
- Sentence Transformers
- RAG
- Embedding Search
  
### Frontend
- Streamlit

### Deployment
- Docker
- Hugging Face Spaces
 
