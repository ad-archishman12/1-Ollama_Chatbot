# 1-Ollama_Chatbot

Intro: 
A lightweight, customizable chatbot built with Ollama for running large language models (LLMs) locally — no cloud dependency, no API keys.

🔍 Features
🦙 Uses local models like llama2, mistral, etc. via Ollama

💬 Supports multi-turn conversations with chat history

🧱 Built with LangChain and Streamlit for modularity and fast UI


⚡ Fast inference with minimal system resources

🚀 Tech Stack
Ollama — local LLM runtime

LangChain — LLM orchestration

Streamlit — UI framework

Python 3.13+

📦 Use Cases
Offline AI assistant

Local coding helper

Lightweight developer tool


Prerequisites
Before running this application, ensure the following:

1. Python 3.8+ is installed on your machine.

2. Install required packages via pip or uv also for faster execution:
pip install -r requirements.txt

3. Ollama must be installed and running locally
Refer to https://ollama.com for installation instructions.

4. Models like llama2, gemma2, or mistral should be available locally in Ollama.
  You can pull them using:
  ollama pull llama2
  ollama pull gemma2
  ollama pull mistral
5. .env file (optional but recommended): You may create a .env file in the root directory to manage environment variables (e.g., for future enhancements like API keys or configuration).




