# Retrieval-Augmented-Generation---Using-Open-AI
Using Open AI LLM to build a Simple RAG


# Simple RAG System - Limpopo Dept of Education

This is a simple Retrieval-Augmented Generation (RAG) project built in Google Colab. It uses an LLM and my content to answer questions based on people around.
Then, approach starts with a simple question fed in an LLM.
Then, add a simple promt to help thre LLM to know how we can Answer.
Create our little vector database and perform word embedding using model="text-embedding-ada-002"
Calculates the dot product between each document embedding and a question_embedding. It then stores the result in a new column called 'distance'.
The Create our RAG using Open AI LLM + prompt


## 🔧 Features

- Load documents (CSV)
- Using Pass through prompt
- Use OpenAI/GPT to generate answers
- Built on Google Colab

## 📁 Files

- `Simple RAG.ipynb`: Main notebook
- `documents/`: Excel file with personal information
- `requirements.txt`: Python dependencies

## 🚀 Getting Started

1. Clone the repo
2. Install dependencies  
   `pip install -r requirements.txt`
3. Open the notebook in Google Colab

## 🔒 Environment Variables

Set your API keys on billed Open AI account:

OPENAI_API_KEY=your-key

