# Pinecone Embedding with OpenAI and LangChain

This repository contains a Jupyter Notebook that demonstrates how to embed data into Pinecone using OpenAI's API, leveraging the LangChain framework to develop LLM-powered applications.

## Overview

The notebook includes code that:

- Sets environment variables for API keys from a `keys.txt` file and user input.
- Loads documents and splits them into chunks using LangChain's text splitter.
- Embeds text using the OpenAI API.
- Stores embeddings in Pinecone, a vector database for similarity search.
- Tests the database with a QA example.
- Adds more transcripts to an existing Pinecone index.

## LangChain

LangChain is an open-source framework designed to help developers integrate large language models (LLMs) with external components, facilitating the creation of AI and machine learning applications. It is especially tuned for crafting applications that capitalize on the power of natural language processing (NLP).

With LangChain, developers can connect robust LLMs such as OpenAI's GPT-3.5 and GPT-4 to various external data sources, thereby enhancing the capabilities of NLP applications. The framework offers packages in Python, JavaScript, and TypeScript.

## Usage

To use the notebook:

1. Clone this repository.
2. Ensure you have Jupyter Notebook installed.
3. Install the required dependencies via `pip install -r requirements.txt`.
4. Add your API keys to the `keys.txt` file or when prompted by the notebook.
5. Run the notebook cells in order.

## Dependencies

The notebook relies on several external libraries:

- `langchain`
- `openai`
- `pinecone-client`

Make sure to install these before running the notebook.

## Security
Ensure that you do not upload your API keys to the GitHub repository. Use environment variables or a secure method to store them when deploying applications.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [OpenAI](https://openai.com/) for the API that enables powerful text embeddings.
- [Pinecone](https://www.pinecone.io/) for the vector database service.
- [LangChain](https://github.com/langchain/langchain) for the framework that makes it possible to build these applications.

