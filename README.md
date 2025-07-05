# My-Projects
📝 AI-Powered Student Profile Analyzer using RAG, LangChain & Gemini
Student Profile Analyzer is an intelligent web-based application that generates highly personalized and professional cover letters for students by analyzing their resumes. It leverages the power of Retrieval-Augmented Generation (RAG) with Google's Gemini LLM, LangChain framework, and FAISS vector search.

Users simply upload their student profile as a PDF, enter job-specific details like company name, address, and position — and the system generates a high-quality, customized cover letter in seconds. The generated letter is also available for download as a formatted PDF.

This project demonstrates the real-world use of LLMs integrated with vector databases, enabling contextual awareness and personalization by retrieving relevant data before generation — the core idea behind modern RAG pipelines.

🚀 Key Features:

📥 Upload your student resume as a PDF

🧠 Automatically analyze resume content using vector search

🔍 Retrieve the most relevant details from the resume for the current job

📝 Generate a customized cover letter with accurate, job-specific context

🌐 Use a beautiful web interface powered by Gradio

📄 Download the generated cover letter as a PDF

🔒 Secure API access using your Google Gemini API key

🧠 Workflow Overview:

Upload student PDF resume 📄

Resume is split into chunks 📚

Chunks are embedded into vectors 🔢

Vectors are stored in FAISS

Retriever pulls context based on student name 🔍

Prompt template is filled with this context and other inputs ✍️

Gemini LLM generates a full cover letter 💬

R) esult is displayed and downloadable as a PDF 📥


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jitesh-011/My-Projects/blob/main/Student_Profile_Analyzer_Project_1_.ipynb)
## 🖼️ Demo

![App Screenshot](./screenshot.png
