# Interactive QA Bot

This repository contains the code for an interactive QA bot that uses Qdrant for retrieval and Cohere for generative responses.

## Features
- Upload PDF documents.
- Generate embeddings for paragraphs.
- Store embeddings in Qdrant vector database.
- Ask questions based on the PDF content.
- Get responses using Cohere's language model.


# Colab Notebook 🚀
   - https://colab.research.google.com/drive/12m2_bls0vHVHWvuLbDMF3f4nL3tUmsWh?usp=sharing

# Live Link 🚀
   ### Hosted on AWS
   - http://13.51.196.211:8501

   
# How it tackle large dataset:
   - Used Batch processing for dealing with large datasets or documents. Here’s why it’s beneficial:

## Efficiency:
   ### Reduced Overhead: 
   - By processing multiple items at once, you reduce the overhead that comes from repeatedly setting up the environment for single operations.

   ### Optimized Resource Use: 
   - It makes better use of computational resources, reducing the time and memory needed for each processing step.

## Speed:
   ### Faster Execution: 
   - Processing items in batches can significantly speed up the overall execution time compared to processing each item individually.
   ### Parallelism: 
   - Batch processing can take advantage of parallel processing capabilities in modern hardware, thus improving throughput.

## Consistency:
   ### Uniformity: 
   - Ensures that all items in a batch are processed under the same conditions, leading to more consistent results.
   ### Error Handling: 
   - It’s easier to implement and manage error handling when processing in batches.

## Practical Application:
   - When embedding text from a PDF, processing in batches allows you to quickly convert large blocks of text into embeddings, rather than doing it one paragraph at a time, which would be slower and less efficient.

   - Helps in scaling up the processing of large documents without significant performance drops, ensuring the system remains responsive even with heavy workloads.

### Batch processing streamlines your entire pipeline, making it robust and scalable. 🚀

   
# Steps to Build and Run the Docker Container 📶

## Build the Docker Image:
- docker build -t qa-bot .

## Run the Docker Container:
- docker run -p 8501:8501 qa-bot

- Visit http://localhost:8501 in your browser to see the running app.


# Deployment Instructions 📶

### Use Virtual Environment (Recommended)
   - Create a new virtual environment using `python -m venv venv` command.
   - Activate virtual environment using `venv\Scripts\activate` (for Windows OS) command.

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


