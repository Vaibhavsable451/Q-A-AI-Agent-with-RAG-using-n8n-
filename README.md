# Q-A-AI-Agent-with-RAG-using-n8n-
🤖 Q&A AI Agent with RAG using n8n

A no-code AI chatbot system that uses Retrieval-Augmented Generation (RAG) to answer questions from custom documents. Built using n8n, Google Gemini, Pinecone, and Google Drive.

🚀 Overview

This project demonstrates a complete RAG-based AI Agent system that can:

Ingest documents
Store embeddings in a vector database
Retrieve relevant context
Generate intelligent answers using an LLM

It eliminates the need for traditional coding by using n8n workflow automation.

✨ Key Features
💬 AI chatbot built using n8n AI Agent
🧠 Powered by Google Gemini (LLM + embeddings)
📂 Document ingestion via Google Drive
🔗 Vector storage using Pinecone
🧠 Memory-enabled conversations (context awareness)
📚 Full RAG pipeline implementation
⚡ Fully customizable no-code workflow
🧰 Tech Stack
n8n – Workflow automation platform
Google Gemini – LLM + embeddings
Pinecone – Vector database
Google Drive – Document storage source
RAG Architecture – Retrieval-Augmented Generation
Vector Embeddings – Semantic search system
⚙️ How It Works
Upload a PDF or document to Google Drive
n8n fetches the file using Google Drive node
Document is split into chunks using Recursive Character Text Splitter
Each chunk is converted into embeddings using Google Gemini
Embeddings are stored in Pinecone vector database
User sends a query to the chatbot
System retrieves relevant chunks from Pinecone
Gemini generates a final contextual response
🧪 Example Use Case

User:
Who is Anaam?

AI Agent:
Anaam Rasool is the founder and CTO of Fast AI agency with experience in software engineering and public speaking.

🛠 Setup Instructions
Import workflow into your n8n instance
Configure credentials:
Google Drive OAuth
Google Gemini API
Pinecone API
Upload your documents to Google Drive
Update file ID in workflow
Activate workflow
Start chatting via webhook or trigger node
📌 Use Cases
Knowledge base chatbot
Document Q&A system
Enterprise AI assistant
Study material chatbot
Customer support automation
📜 License

This project is open-source and available under the MIT License.

⭐ Built With

n8n • Google Gemini • Pinecone • RAG • AI Automation
