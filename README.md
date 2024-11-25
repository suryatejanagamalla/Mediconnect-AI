# Medical_Assistant

Healthcare Access Enhancement Project
This repository contains the implementation of a project aimed at easing healthcare access and reducing the workload on doctors and patients by leveraging advanced AI and machine learning techniques. The project is built on the integration of audio-to-text conversion, text summarization, a Retrieval-Augmented Generation (RAG) model, and a user-friendly app platform for streamlined healthcare interactions.

Project Overview
Objective
To simplify healthcare access and assist medical practitioners by:

Extracting meaningful insights from medical call recordings between practitioners and patients.
Providing a symptom-checker chatbot for quick diagnosis and recommendations.
Features
Patient Insights
Summarizes audio recordings into concise insights, highlighting key patient information.
Symptom Checker
A medical chatbot that provides possible diagnoses and remedies based on real-time data and symptom inputs.
Project Workflow
1. Data Collection
Simulated 272 medical call recordings between practitioners and patients, focusing on:
Respiratory diseases
Musculoskeletal diseases
Cardiac diseases
Dermatological diseases
Gastrointestinal diseases
2. Architecture
Audio-to-Text Conversion
Leveraged advanced transcription tools to convert medical call recordings into textual data.
Text Summarization and Key Attribute Extraction
Extracted critical medical attributes (symptoms, diagnoses, medications) from text data.
RAG Model Integration
Built a Retrieval-Augmented Generation (RAG) model:
Integrated Large Language Models (LLMs) with vector databases for efficient information retrieval.
App Development
Created a Streamlit-based application to deliver insights and chatbot functionalities.
Technical Stack
Technologies and Tools
Programming Language: Python
Frameworks:
Streamlit (for the app platform)
Pydub (for audio processing)
Libraries:
OpenAI (for LLM integration)
LangChain (for RAG model development)
Sentence Transformers (for embedding generation)
Database: Pinecone (vector database)
Other Tools:
Whisper (audio-to-text conversion)
Key Files
requirements.txt: Lists all dependencies for the project.
