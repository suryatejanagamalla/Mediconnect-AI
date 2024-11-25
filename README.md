# Medical_Assistant

# Healthcare AI Assistant

This repository contains a project designed to streamline healthcare access and reduce the workload on doctors and patients by utilizing advanced AI techniques. The solution is built to process medical call recordings between practitioners and patients, extract meaningful insights, and provide intelligent healthcare support through a user-friendly application.

## Overview

The project focuses on handling audio data to create a comprehensive healthcare assistant. It incorporates AI-driven methods to process call recordings related to respiratory, musculoskeletal, cardiac, dermatological, and gastrointestinal diseases. The resulting application serves two primary purposes:

1. **Patient Insights**: Summarizes patient-practitioner conversations into actionable insights.
2. **Symptom Checker**: A chatbot that suggests possible diseases and remedies based on real-time data.

---

## Architecture

The solution is implemented in the following steps:

1. **Audio-to-Text Conversion**  
   - Converts audio call recordings into textual transcripts for further analysis.
   
2. **Text Summarization and Key Attribute Extraction**  
   - Summarizes the transcribed conversations.
   - Extracts key attributes (symptoms, diagnoses, prescriptions, etc.) for processing.

3. **RAG Model Implementation**  
   - Built a **Retrieval-Augmented Generation (RAG)** model by integrating Large Language Models (LLMs) with vector databases for efficient data retrieval and response generation.

4. **Application Development**  
   - Developed a user-friendly interface using **Streamlit**, providing the following features:
     - **Patient Insights**: Displays summarized views of audio recordings for quick review by practitioners and patients.
     - **Symptom Checker**: An interactive chatbot that suggests possible diseases and remedies based on user input and real-time data.

---

## Features

- **Audio-to-Text Conversion**: Seamlessly converts medical calls into structured textual data.  
- **Summarization and Insights**: Provides concise summaries of patient data for efficient decision-making.  
- **Symptom Checker**: Suggests probable diseases and remedies using intelligent algorithms and real-time information.  
- **Streamlit Integration**: Offers an easy-to-use app platform for both practitioners and patients.  

---

## Requirements

The project includes a `requirements.txt` file that lists all necessary dependencies. 
