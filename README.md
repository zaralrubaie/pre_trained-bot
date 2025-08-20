# Pre_Trained Bot - Rule-Based + DialoGPT Chatbot 🤖💬

[![Python](https://img.shields.io/badge/python-3.8+-blue)](https://www.python.org/)  
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Spaces-orange)](https://huggingface.co/)

---

## 🔹 Project Overview

**Pre_Trained Bot** is a simple chatbot combining **rule-based responses** with a **pretrained model (`DialoGPT-small`)** to handle open-ended conversations.  
This project demonstrates how to build and deploy a chatbot using:

- [Hugging Face Transformers](https://huggingface.co/transformers/)  
- [Gradio](https://gradio.app/) for the web interface  

The bot includes:  
- Rule-based responses for common greetings  
- Generative replies for other user inputs using DialoGPT-small  

---

## 🔹 Features

- Predefined responses for greetings and FAQs  
- Dynamic responses via DialoGPT-small  
- Simple Gradio UI for interaction  
- Runs on CPU (no GPU required)  

---

## 🔹 Deployment

- Deployed on Hugging Face Spaces using `requirements.txt` for dependencies.  
- Temporary deployment via Google Colab for 7 days: [Live Demo](https://df987044db541eb781.gradio.live)  

---

## 🔹 Usage

1. Type messages into the chat box  
2. Predefined greetings will return instant responses  
3. Other messages are handled dynamically by DialoGPT-small  
4. Chat history is limited; the bot works best for short conversations  

---

## 🔹 Limitations & Future Work

- Currently uses **DialoGPT-small**, which may produce generic or repetitive answers  
- Laptop hardware limits training of larger models  
- Conversation history is limited and not optimized for long interactions  
- Future improvements:  
  - Better prompt formatting  
  - Upgrading to more powerful models  
  - Saving chat history  
  - Adding a reset button  
  - Improved UI styling  
  - Fix deployment issues on Hugging Face Spaces  

---

## 🔹 Prerequisites

- Python 3.8+  
- Pip (Python package manager)  

---

## 🔹 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/zaralrubaie/pre_trained-bot.git
cd pre_trained-bot
```
2. Install dependencies:
   
 ```bash
pip install -r requirements.txt
 ```
3. Run the chatbot:
 ```bash
python app.py
```
## 🔹 Project Structure
- app.py - Main application file with Gradio interface
- requirements.txt - Python dependencies
- README.md - Project documentation

## 🔹 Contact
- Zahraa — engzahra0083@gmail.com
- GitHub: zaralrubaie 
