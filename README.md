# RAG Chatbot for Docker Education Using LlamaIndex, Groq, and Llama3

## Overview

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) chatbot designed to educate data scientists about Docker. The chatbot utilizes LlamaIndex for indexing, Groq for LLM (Large Language Model) interactions, and Llama3 for generating responses. The chatbot is specifically tailored to provide comprehensive explanations on Docker concepts and practices, leveraging a book as its primary data source.

## Features

- **Educational Focus:** Provides detailed explanations on Docker, aimed at data scientists.
- **Customizable:** Users can replace the book with other resources to tailor the chatbot to different topics or databases.
- **Advanced AI Integration:** Utilizes LlamaIndex for indexing and Groq with Llama3 for processing queries and generating responses.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**

   First, clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name

2.  **Install Requirements**

    Install the necessary Python packages listed in `requirements.txt`:
    pip install -r requirements.txt

3.  **set Up API Key**

    Ensure you have your API key for Groq. Set up the API key in your environment. 

4.  **Run the Notebook**

    Open the provided Jupyter notebook and execute the cells to start using the chatbot. The notebook will guide you through the process of loading data, creating the index, and querying the chatbot.

    jupyter notebook

5.  **Customizing the Chatbot**

    You can replace the provided Docker book with any other resource to adjust the chatbot's focus. Update the SimpleDirectoryReader input to point to your new resource file.