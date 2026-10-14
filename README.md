Week 4: AI Agent Systems
Project Overview
This project implements a Retrieval-Augmented Generation (RAG) system using LangChain, LangGraph, FAISS, and a local FLAN-T5 model.

Technologies Used
Python
LangChain
LangGraph
FAISS Vector Store
Hugging Face Transformers
FLAN-T5
Google Colab
LangSmith (tracing setup attempted)
Project Workflow
Prepare AI and ML notes as the knowledge source.
Split the text into smaller chunks.
Generate embeddings and store them in FAISS.
Retrieve relevant context for user questions.
Generate answers through the LangGraph workflow.
Test the system with multiple questions and save evaluation results.
Files
Week4_AI_Agent_Systems.ipynb — Project implementation
rag_evaluation_results.csv — Evaluation results
Evaluation
The system was tested with six questions related to AI, Machine Learning, Deep Learning, NLP, Computer Vision, and AI applications.

The evaluation CSV contains the recorded results. LangSmith tracing was attempted, but traces were not confirmed in the dashboard.

Status
The RAG workflow and evaluation are completed. Further verification of LangSmith tracing remains pending.
