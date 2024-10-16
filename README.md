# Interactive QA Bot

This repository contains the code for an interactive QA bot that uses Qdrant for retrieval and Cohere for generative responses.

## Features
- Upload PDF documents.
- Generate embeddings for paragraphs.
- Store embeddings in Qdrant vector database.
- Ask questions based on the PDF content.
- Get responses using Cohere's language model.

# Steps to Build and Run the Docker Container:

## Build the Docker Image:
- docker build -t qa-bot .

## Run the Docker Container:
- docker run -p 8501:8501 qa-bot

- Visit http://localhost:8501 in your browser to see the running app.

# Deployment Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Irshad-Ahmaed/ragbot_streamlit.git
   cd ragbot_streamlit

2. **Install dependencies**;
   ```sh
   pip install -r requirements.txt

3. **Run the Streamlit app**;
   ```sh
   streamlit run rag.py


