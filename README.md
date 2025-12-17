This project is a simple Retrieval-Augmented Generation (RAG) pipeline built inside a Colab notebook. It loads a PDF, chunks the text, generates embeddings, stores them in ChromaDB, answers questions using OpenAI GPT-4o-mini, and evaluates the system using RAGAS with a free HuggingFace model.

***Features

PDF text extraction

Text chunking (LangChain)

Embeddings with OpenAI

Vector storage using ChromaDB

RAG question-answering

RAGAS evaluation (faithfulness, relevancy, correctness, precision, recall)

***How to Use

Open the notebook in Google Colab

Upload your PDF

Enter your OpenAI API key

Run all cells in order

Ask questions + view evaluation scores
