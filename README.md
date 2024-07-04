# Chat with PDF
This project is a Streamlit-based web application that allows users to upload PDF files and ask questions about the content. The application uses Google Generative AI and FAISS for embedding and similarity search, enabling detailed question answering from the provided PDFs.

## Features
* PDF Upload: Users can upload multiple PDF files.
* Text Extraction: Extracts text from the uploaded PDF files.
* Text Chunking: Splits the extracted text into manageable chunks.
* Vector Store: Creates and saves a FAISS vector store from the text chunks.
* Question Answering: Allows users to ask questions about the PDF content, providing detailed answers using Google Generative AI.

## Dependencies
* Streamlit: For building the web application.
* PyPDF2: For extracting text from PDF files.
* Langchain: For text chunking and question answering.
* Google Generative AI: For embedding and conversational AI.
* FAISS: For similarity search in the vector store.
* dotenv: For loading environment variables.

## Media
Attached below are the final video and photo of the chatbot working.