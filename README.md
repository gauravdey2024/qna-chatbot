An end-to-end Retrieval-Augmented Generation (RAG) system built with LangChain, Google Gemini, and ChromaDB to perform question answering over domain-specific PDF documentation with conversational memory, LangSmith tracing, and automated Ragas evaluation.



Features:


-PDF Ingestion \& Processing: Loads and splits PDF documents using PyPDFLoader and RecursiveCharacterTextSplitter.  


-Vector Storage: Stores document embeddings in a Chroma vector store utilizing GoogleGenerativeAIEmbeddings (models/gemini-embedding-001).  


-Context-Aware Conversational Memory: Maintains ongoing dialogue context with ChatMessageHistory and dynamic prompt templating.


-Generation Model: Powered by Google's gemini-2.5-flash model via ChatGoogleGenerativeAI.  


-Observability: Full run logging and tracing integrated with LangSmith.


-Evaluation: Automated RAG pipeline assessment using Ragas evaluating Faithfulness, Answer Relevancy, Context Precision, and Context Recall.

