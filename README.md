VOID AI 🛡️🤖

VOID AI is a cutting-edge, unrestricted local security and penetration testing assistant built entirely from scratch using Python, LangChain, and Ollama. Designed specifically to run locally within a Kali Linux environment, VOID AI empowers security professionals and developers with full AI automation without compromising data privacy or depending on external cloud APIs.
🚀 Key Highlights & Effectiveness

100% Offline & Private: Runs completely air-gapped on your local hardware. No data or prompts ever leave your machine, ensuring absolute confidentiality.

Unrestricted & Filtered-Free: Unlike commercial cloud-based LLMs bogged down by heavy safety guardrails and corporate restrictions, VOID AI operates with zero artificial filters, giving you raw, direct utility for security research and command orchestration.

Local CPU/GPU Optimized: Engineered to seamlessly leverage lightweight, high-efficiency models (such as phi3) optimized for local execution.

Modular Architecture: Cleanly separated design featuring a powerful orchestrator (main.py) paired with a robust execution backend (tools.py) for direct system and terminal interaction.

⚙️ Installation & Quick Start

To set up and run VOID AI locally on your system, follow these steps:

 1.Clone the repository:
 

    git clone https://github.com/meso78/void-ai.git
    cd void-ai

2.Setup Python Virtual Environment:


    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

3.Install and Run Ollama:
Make sure Ollama is installed on your local machine, then pull your preferred lightweight model:


    ollama pull phi3

4.Run the Agent:


    python3 main.py
