# Multipdf-chat-app

This application allows users to upload multiple PDF files and interact with them using natural language queries. The system extracts text from PDFs, processes it into embeddings, stores it in a FAISS vector database, and uses Google's Gemini AI to generate intelligent responses.

 Features
Upload multiple PDF documents
Extract and store text in FAISS vector storage
Use Google Gemini AI to process and answer queries
Efficient chunking of text for better retrieval
Interactive UI using Streamlit

Technologies Used
Python
Streamlit (Frontend UI)
PyPDF2 (PDF text extraction)
LangChain (Chunking, Retrieval, AI Chain)
FAISS (Vector database)
Google Generative AI (Gemini AI for answering queries)
dotenv (Environment variable management)

 Future Enhancements
Support for image-based PDFs (OCR integration)
Multilingual support
