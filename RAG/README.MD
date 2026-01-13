## Workflow: RAG System (Google Drive + Gemini + Pinecone)

This workflow automates a **Retrieval-Augmented Generation (RAG)** pipeline.

### Overview
- **Source:** Form or Google Drive folder  
- **Processing:** Splits text and generates embeddings using Google Gemini  
- **Vector Store:** Stores and queries vectors in Pinecone  
- **AI:** Answers questions based on the retrieved documents  

### Required Configuration
- Google Drive API credentials  
- Google Gemini API key  
- Pinecone API key and environment  
