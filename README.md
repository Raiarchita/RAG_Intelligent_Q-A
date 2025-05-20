# RAG_Intelligent_Q-A
Built a LangGraph-powered RAG Q&A system integrated with: 
o AstraDB (vector store) to manage embeddings of internal documentation, 
o Groq-hosted Gemma2 LLM for ultra-fast inferencing. 
o The LLM acts as a router, determining whether the user query should be answered via: 
o Internal knowledge base (MiniLM + HuggingFace embeddings), given as blogs or 
documents. 
o Or external sources like Wikipedia or ArXiv via API-based scraping or summarization. 
o LangGraph orchestrates the modular workflow of document retrieval, query 
classification, and response generation.
