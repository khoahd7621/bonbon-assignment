# Chatbot for IT Support

## Overview

This project aims to create a chatbot solution designed to assist users with IT-related inquiries. The chatbot leverages a variety of tools and technologies, including LangChain and Azure OpenAI, to provide accurate and context-aware answers to frequently asked questions (FAQs) from the BonBon FAQ.pdf document. The solution is built to support customer service scenarios, addressing issues related to networking, software, and hardware.

## Features

- **Document Indexing**: Indexing of the BonBon FAQ.pdf to a local Chroma vector database for efficient retrieval.
- **Question-Answering**: Utilizes the Azure OpenAI model for generating answers based on the indexed document.
- **Conversational Agent**: Implements a conversational agent that interacts with users, maintaining context throughout the chat.
- **Web Search**: Integrates internet search capabilities to provide additional information when needed.
- **Source Referencing**: Each response includes references to the original source document and the page number for transparency.

## Technologies Used

- **Python**: The primary programming language for the project.
- **LangChain**: A framework for building applications with language models.
- **Azure OpenAI**: For utilizing advanced language models and embeddings.
- **Chroma**: For managing and querying vector databases.

## Requirements

- Python installed on your system
- Jupyter environment set up in PyCharm or Visual Studio Code

## Setup

1. Clone this repository
2. Open this project in your preferred IDE
3. Launch your Jupyter Notebook environment
4. Open `assignment.ipynb` and follow the steps to run it

## Contact

If you need any further assistance or source code, please contact your training team.