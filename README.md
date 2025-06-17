pre_trained-bot
# Simple Rule-Based Chatbot with DialoGPT

This is a lightweight chatbot project built with Hugging Face Transformers. It uses a mix of predefined rules and a pretrained model (`microsoft/DialoGPT-small`) to respond to basic questions.

---

##Features
- Responds to greetings, questions like "what is your name", and common chat phrases
- Uses a fallback text-generation model (DialoGPT-small)
- Runs locally on CPU
- Saves the conversation to `dialogs.txt`

---
# Files

- `app.py` — Main Python chatbot script
- `dialogs.txt` — Logged conversation (generated after each chat)
- `README.md` — Project documentation

---

# How to Run

Make sure you have Python installed.

 Install required libraries:
```bash
pip install transformers
python app.py
