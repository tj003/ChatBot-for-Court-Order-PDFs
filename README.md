⚖️ Conversational RAG for Court Order PDFs
This project is a Conversational Retrieval-Augmented Generation (RAG) app built with LangChain, HuggingFace embeddings, and Groq LLMs.

👉 Live Demo on Hugging Face Spaces

It allows you to:

📄 Upload digital or scanned court order PDFs

🔍 Extract and index the content (OCR for scanned docs using doctr)

💬 Ask natural language questions about the uploaded documents

🧠 Get AI-powered answers with conversation history

🚀 Features
Supports Digital & Scanned PDFs (via OCR)

Semantic Search with HuggingFace MiniLM embeddings

LLM-powered QA using Groq (Gemma2-9b-It)

Conversation Memory (keeps context across queries)

Streamlit UI (easy to use in browser)

🔑 Requirements
Python 3.10+

A Groq API Key

📝 Getting Your Groq API Key
Go to Groq Console

Sign up / log in

Navigate to API Keys section

Click Create API Key

Copy the key (it will look like gsk_xxx...)

You’ll need this API key when using the app.

💡 Usage
Open the Live App

Enter your Groq API Key in the input field

Choose Digital PDF or Scanned Document (OCR)

Upload your PDF(s)

Ask questions like:

“What was the judgment in this case?”

“Which section of the law was cited?”

“Who are the parties involved?”

📦 Tech Stack
LangChain – RAG pipeline, retrievers, memory

Groq – Fast & efficient LLM inference (Gemma2-9b-It)

HuggingFace – MiniLM embeddings

doctr – OCR for scanned PDFs

Streamlit – UI

👨‍💻 Author
Built by Tushar Jadhav 🚀
LinkedIn: https://www.linkedin.com/in/tusharj13/

👉 Try it live here: https://huggingface.co/spaces/TJ003/Law-pdf-chat

