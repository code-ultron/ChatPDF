# Chat_with_Multiple_PDF_llama2_Pinecone
This repository contains a Python script for extracting text from PDF documents, creating embeddings, 
and performing similarity searches using Pinecone. 
It also demonstrates a question-answering system using the Llama2 model via Hugging Face.

# Usage Instructions

Load PDF Files:
The script downloads PDF files and stores them in a "pdfs" folder.

Extract Text from PDFs:
The extracted text is split into smaller text chunks for processing.

Create Embeddings:
Embeddings are generated using the Sentence Transformers library.

Pinecone Setup:
Pinecone is initialized for similarity searches. Ensure you have a Pinecone API key and environment variables set up.

Perform Similarity Searches:
Query the Pinecone index to find similar text chunks.

Llama2 Model Wrapper:
The Llama2 model is set up for text generation and question-answering.

Create a Prompt Template:
Define a template for questions and context.

Question-Answering System:
Use the system to ask questions based on the available context.

# Example Usage

Here are some example queries and responses:

Query: "YOLOv7 outperforms which models"
Response: "Based on the provided context, YOLOv7 outperforms..."

Query: "What is Rachel Green qualification"
Response: "Based on the provided context, Rachel Green's qualification is..."
