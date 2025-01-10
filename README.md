# PDF-SUMMARIZER-RAG-PROJECT
I have created a PDF summarizer, that can summarize the content of research papers
Usage
This project uses a pipeline that consists of the following steps:

Load and process documents using PyPDFLoader and a text splitter.
Generate embeddings for the documents using GoogleGenerativeAIEmbeddings.
Create a vectorstore from the documents and embeddings using Chroma.
Retrieve relevant documents for a given query using the vectorstore.
Use ChatGoogleGenerativeAI to answer the question based on the retrieved documents.

This project utilizes the following libraries:

1)langchain_community: A collection of tools for building language chain models.
2)pypdf:  A library for working with PDF documents in Python.
3)langchain_google_genai: Enables access to Google Generative AI services from Langchain.
4)langchain_chroma: A library for building and managing dense vector representations of text.

These libraries are used to build a system for question answering tasks using a combination of document retrieval and generative AI. The system retrieves relevant passages from a PDF document and uses a generative AI model to answer questions based on the retrieved context.
