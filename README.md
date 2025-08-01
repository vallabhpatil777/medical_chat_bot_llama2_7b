# 🩺 Medical Chatbot – Fine-tuned LLaMA 2–7B

This is a conversational AI chatbot powered by a **fine-tuned LLaMA 2–7B** model, trained on curated **medical text data** to provide accurate, concise, and helpful responses to medical queries.

## Features

- Fine-tuned using instruction-style medical Q&A pairs
- Capable of answering health-related questions responsibly
- Deployed with a user-friendly Gradio chat interface

## Model

- **Base Model**: `meta-llama/Llama-2-7b-chat-hf`
- **Fine-tuned on**: Domain-specific medical prompts and completions
- **Frameworks Used**: Hugging Face Transformers, PEFT (LoRA), Gradio

## Setup & Run (Locally)

```bash
git clone https://github.com/vallabhpatil777/medical-chatbot
cd medical-chatbot
pip install -r requirements.txt
python app.py


## Snapshot
<img width="3456" height="2000" alt="image" src="https://github.com/user-attachments/assets/ac567077-6e9f-435c-be40-2db86c578cb4" />

