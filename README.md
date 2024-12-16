# Website Chat with RAG Pipeline

## Project Overview
This project implements a *Retrieval-Augmented Generation (RAG) pipeline* to enable users to interact with structured and unstructured data from websites. The system can scrape website content, convert it into embeddings, store it in a vector database, and generate context-rich responses to user queries using an LLM.

## Features
- Crawl and scrape data from websites.
- Split content into chunks for better processing.
- Generate embeddings using pre-trained models.
- Store embeddings in a vector database (ChromaDB) for similarity search.
- Use an LLM (like GPT-2 or GPT-J) to generate context-rich responses.

## How to Run

### Step 1: Install Dependencies
1. Clone this repository:
   ```bash
   git clone https://github.com/Himavarshac/Website-chat-RAG-Pipeline.git
   cd Website-chat-RAG-Pipeline