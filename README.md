# Chatbot - Streamlit-based PDF Chatbot

A chatbot application built using Streamlit that enables interaction with custom PDF documents by leveraging natural language processing and vector databases.

## Table of Contents
- [Background](#background)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Background
This chatbot application allows users to upload PDF documents and query their content using a conversational interface. It employs embeddings and vector stores to retrieve relevant information efficiently.

## Features
- **PDF Upload**: Users can upload multiple PDFs for processing.
- **Natural Language Processing**: Queries are processed using advanced language models.
- **Vector Database Integration**: Efficient retrieval of information using FAISS.
- **Chat History**: Maintains context-aware responses.
- **Custom Styling**: Uses HTML and CSS for a structured chat interface.

## Technologies Used
- **Python**: Core programming language
- **Streamlit**: Web framework for UI development
- **Natural Language Processing**:
  - OpenAI API / HuggingFace
  - Embeddings (HuggingFaceInstructEmbeddings, OpenAIEmbeddings)
- **PDF Handling**:
  - PyPDF2 for text extraction
- **Vector Database**:
  - FAISS for similarity search
- **Web Development**:
  - HTML/CSS for styling

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shwetamadhale/ChatbotApp.git
   ```
2. Navigate to the project directory:
   ```sh
   cd ChatbotApp
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```

## Usage
1. **Upload PDF files** via the sidebar.
2. **Ask questions** based on the uploaded documents.
3. **Receive AI-generated responses** with context from the documents.


