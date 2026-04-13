Advanced RAG Q&A System
This repository contains a Retrieval-Augmented Generation (RAG) application built with Streamlit, LangChain, and Hugging Face. The system allows users to upload various document types or provide web links, creates a searchable vector database using FAISS, and answers natural language questions using the Meta-Llama-3-8B-Instruct model.

🚀 Features
Multi-source Input: Supports PDF, DOCX, TXT files, direct text input, and Web URLs.

Vector Search: Utilizes FAISS and sentence-transformers/all-mpnet-base-v2 for high-performance similarity search.

LLM Integration: Powered by Meta-Llama-3-8B-Instruct via Hugging Face Endpoints.

User Interface: Clean and interactive UI built with Streamlit.

🛠️ Technical Stack
Frontend: Streamlit

Orchestration: LangChain

Vector Database: FAISS

Embeddings: Hugging Face Transformers

LLM: Meta Llama 3 (8B Instruct)

📋 Prerequisites
Before running the application, ensure you have:

Python 3.8 or higher.

A Hugging Face API Token (with access to Llama 3).

🔧 Installation & Setup
Clone the Repository:

Bash
git clone <repository-url>
cd Advanced-RAG-Q-A-System
Install Dependencies:

Bash
pip install -r requirements.txt
Configure API Keys:
Create a file named secret_api_keys.py in the root directory and add your Hugging Face token:

Python
huggingface_api_key = "your_huggingface_api_token_here"
💻 Usage
Run the Streamlit App:

Bash
streamlit run app.py
Interact with the System:

Select Input Type: Choose from Link, PDF, Text, DOCX, or TXT.

Upload/Provide Data: Follow the UI prompts to upload your file or enter URLs.

Process: Click the "Proceed" button to generate the vector embeddings.

Ask Questions: Type your query in the text box and click "Submit" to receive an AI-generated answer based on your data.

