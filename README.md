# Interactive QA Bot

This repository contains the code for an interactive QA bot that uses Qdrant for retrieval and Cohere for generative responses.

## Features
- Upload PDF documents
- Ask questions based on the content of uploaded documents
- Get real-time answers with relevant document segments

## Steps to Build and Run the Docker Container:

# Build the Docker Image:
- docker build -t qa-bot .

# Run the Docker Container:
- docker run -p 8501:8501 qa-bot

- Visit http://localhost:8501 in your browser to see the running app.

## Deployment Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Irshad-Ahmaed/RagBot.git
   cd your-repo-name

