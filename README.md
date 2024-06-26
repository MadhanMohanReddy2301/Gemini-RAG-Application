# Chat PDF with Gemini 💁

This Streamlit application allows users to interact with PDF documents using conversational AI powered by Gemini and Google's generative AI.

## Features

- **Upload PDF Files**: Users can upload multiple PDF documents.
- **Process PDFs**: Extracts text from uploaded PDFs and creates text chunks for indexing.
- **Search and Chat**: Users can ask questions related to the PDF content and receive answers using a combination of FAISS vector search and generative AI.

## Requirements

- Python 3.7+
- Libraries specified in `requirements.txt`
- Google API Key configured via environment variable `GOOGLE_API_KEY`

## Installation

1. **Clone the repository:**

   ```bash
   git clone <https://github.com/MadhanMohanReddy2301/Gemini-RAG-Application.git>
   cd <Gemini-RAG-Application>
