# Long-context-QA-System
This project implements a simple Long-Context Question Answering (QA) system that can process large pieces of text and retrieve the most relevant information to answer a user's question.

The system follows a Retrieval-based approach similar to Retrieval-Augmented Generation mini (RAG). Instead of giving the entire document to the model, the text is first divided into smaller chunks, converted into vector embeddings, and stored in a vector index. When a user asks a question, the system retrieves the most relevant chunks and generates an answer based on the retrieved context.
