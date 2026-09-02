🎥 GenAI-Powered YouTube Video Summarizer & Q&A System using RAG

📌 Project Overview

This project is a Retrieval-Augmented Generation (RAG) application that summarizes YouTube videos and answers user questions based on the video content. The system extracts YouTube transcripts, converts them into embeddings, stores them in a FAISS vector database, and uses Google's Gemini LLM to generate accurate and context-aware responses.

🚀 Features
Extract transcript from any YouTube video
Generate concise video summaries
Ask natural language questions about video content
Semantic search using FAISS Vector Store
Retrieval-Augmented Generation (RAG) pipeline
Context-aware answers using Gemini LLM
Interactive command-line interface

🏗️ Architecture

YouTube Video URL
⬇️
Transcript Extraction
⬇️
Text Chunking
⬇️
Hugging Face Embeddings
⬇️
FAISS Vector Database
⬇️
Retriever
⬇️
Gemini LLM
⬇️
Summary / Question Answering

🛠️ Technologies Used
Python
LangChain
Google Gemini API
Hugging Face Embeddings
FAISS Vector Database
YouTube Transcript API
Retrieval-Augmented Generation (RAG)
Natural Language Processing (NLP)

📂 Project Workflow
Extract transcript from YouTube video.
Split transcript into smaller chunks.
Generate embeddings using Hugging Face.
Store embeddings in FAISS Vector Store.
Retrieve relevant chunks based on user query.
Send retrieved context to Gemini LLM.
Generate summary or answer.

💡 Sample Questions
What is the main topic of the video?
Summarize this video in 5 points.
What did the speaker say about AI?
Explain the key concepts discussed.

🎯 Future Enhancements
Support multiple YouTube videos
Web-based interface using Streamlit
Quiz generation from video content
PDF report generation
Multi-language support

👨‍💻 Author

Abhishek Singh

M.Sc. (Statistics) Student | Data Science & AI Enthusiast
