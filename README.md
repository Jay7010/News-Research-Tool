AI-Powered News Research Tool

Overview

This AI-driven research tool is designed to extract financial and stock market insights from news articles. It utilizes LangChain's UnstructuredURLLoader, Cohere embeddings, and FAISS to enable efficient retrieval and analysis of relevant information.

Features

Automated News Analysis: Enter up to 3 URLs to extract content automatically.

AI-Powered Question Answering: Get relevant financial insights from articles.

FAISS-Based Search: Efficiently indexes and retrieves text based on similarity.

User-Friendly Interface: Streamlit-powered interactive UI.

Project Structure

project/
│── main.py              # Streamlit application script
│── requirements.txt     # Required dependencies
│── faiss_index.pkl      # FAISS index for optimized retrieval
│── .env                 # API keys (Cohere, LangChain, etc.)
└── README.md            # Project documentation

Installation

Prerequisites

Python 3.8+

Virtual environment (recommended for dependency management)

Installing Dependencies

Run the following command in your terminal to install all required dependencies:

pip install -r requirements.txt

Usage

Enter up to 3 news article URLs in the Streamlit sidebar.

Ask financial or stock market-related questions.

View AI-generated insights based on retrieved content.

Technologies Used

Streamlit: Web-based UI framework.

LangChain: Manages document retrieval and processing.

UnstructuredURLLoader: Extracts text from provided URLs.

Cohere Embeddings: Converts text into AI-readable format.

FAISS: Enables fast and efficient similarity-based searches.

Future Enhancements

Support for multi-language news articles.

Advanced summarization and sentiment analysis.

Integration with live financial data sources.
