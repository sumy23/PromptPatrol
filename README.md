# PromptPatrol 

Security Testing and Risk Analysis of LLMs Against Prompt Injection Attacks

PromptPatrol is a modular and lightweight framework to test the security robustness of Large Language Models (LLMs) like GPT-4. It simulates prompt injection scenarios and classifies model responses into ethical, illegal, or harmful categories.

##  Features

- GPT-4 prompt injection testing (OpenAI API)
- Rule-based risk classification
- Interactive UI with Gradio
- Risk report generation (CSV, charts)

##  Tech Stack

- Python, Gradio, OpenAI API, pandas, matplotlib, dotenv

##  Run Locally

```bash
git clone https://github.com/kullanici-adin/PromptPatrol.git
cd PromptPatrol
pip install -r requirements.txt
python src/main.py
# PromptPatrol
LLM Security Testing Framework for Prompt Injection Attacks
