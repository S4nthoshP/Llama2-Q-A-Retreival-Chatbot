# Llama-2 Q&A Retrieval Chatbot

This project is a Python-based Q&A retrieval chatbot powered by the Llama-2 Large Language Model (LLM). The chatbot enables users to upload documents of their choice and interact with the bot to retrieve specific information or receive summaries from the uploaded content.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Acknowledgments](#acknowledgments)

## Features

- **Document Upload:** Users can upload one or multiple documents for the chatbot to process.
- **Information Retrieval:** Ask the chatbot specific questions about the uploaded documents, and it will retrieve relevant information.
- **Content Summarization:** The chatbot can also provide summaries of the uploaded content.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/S4nthoshP/llama-2-qa-retrieval-chatbot.git
   cd llama-2-qa-retrieval-chatbot

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage
1. Run the main application.
2. Upload your documents and ingest it.
3. Interact with the chatbot by asking questions or requesting summaries.

## Files

- **Q&A -- Main App.py**: The main application script that orchestrates the chatbot’s functionalities.
- **constants.py**: Contains configuration constants used across the project.
- **ingest.py**: Handles the document ingestion process.
- **load_models.py**: Contains the functions required to load and initialize the Llama-2 model.
- **prompt_template_utils.py**: Provides utility functions for creating and managing prompt templates.
- **requirements.txt**: Lists all the Python dependencies required to run the project.

## Acknowledgements
- **Llama-2** by Meta for the powerful language model.
- **Center of Developement of Advanced Computation(CDAC)** for providing the resources and support during the internship.
   
