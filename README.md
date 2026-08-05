# VOID AI

An unrestricted local AI penetration testing assistant built from scratch using Python, LangChain, and Ollama. Designed to run locally on Kali Linux for privacy and automation.

## Features
- Direct execution of system commands and Kali tools via Python subprocess.
- Local execution using Ollama (supports Llama 3, Phi-3, etc.) with no external API filters.
- Modular architecture (`main.py` for orchestration, `tools.py` for system execution).

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/void-ai.git](https://github.com/meso78/void-ai.git)
   cd void-ai

Setup Python Virtual Environment:

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

Install and Run Ollama:
Make sure Ollama is installed and run your preferred lightweight model:

ollama pull phi3

run the agent:

python3 main.py
