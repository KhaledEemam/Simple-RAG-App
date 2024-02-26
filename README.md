# RAG (Retrieval-Augmented Generation) Application

## Overview
In this project, I built a simple RAG app that loads a PDF document, splits it into small chunks, converts these chunks into embeddings using the embeddings LLM, stores these embeddings 
in a Chroma vector database. Then, I used the stuff chain from LangChain to get answers for the user's questions by having the LLM look through the most similar text chunks to the entered
question.To test this app, I asked ChatGPT to act as a sports reporter covering the World Cup 2026 and write a series of articles for me. Then, I used these articles as my PDF document and asked the RAG
app about this event.

## Repository Contents
* Notebook: Contains the Python notebook implementing the RAG application.
* Articles PDF: A collection of sports articles related to the 2026 FIFA World Cup.
* Chromedb Vectorstore: Stores vector representations of the articles for efficient similarity search and retrieval.
* requirements.txt: Lists the dependencies required to run the RAG application.
