pre_trained-bot

## Project Overview
Simple Rule-Based Chatbot with DialoGPT,a lightweight chatbot built with Hugging Face Transformers and Gradio. It combines predefined rule-based responses with a pretrained model (`DialoGPT-small`) to handle open-ended conversations.
This project demonstrates how to build and deploy a chatbot using:

- [Transformers](https://huggingface.co/transformers/)
- [Gradio](https://gradio.app/) for the web UI
 It includes:
- Rule-based responses for common greetings
- Generative replies for other questions using DialoGPT-small
   
## Features
- Predefined responses for greetings and FAQs
- Dynamic responses with DialoGPT-small
-  Simple Gradio UI for interaction
- Runs on CPU (no GPU required)
  
#Deployment
This chatbot is deployed as a Hugging Face Space. The requirements.txt ensures the necessary libraries are installed during deployment.
deployment was on colab notebook for 7 days only:  https://df987044db541eb781.gradio.live

Usage:
Type messages into the chat box
Some greetings have predefined answers for quick responses
For other inputs, the chatbot generates replies using DialoGPT

Limitations and Future Work:
Currently uses DialoGPT-small, which can produce generic or repetitive answers
laptop couldnt handle large models to train better bots 
Conversation history is limited and not optimized for long interactions
Plans to improve prompt formatting and switch to more powerful models
Adding features like chat history saving, reset button, and better UI styling
Face problem in deploment in hugging face 
###Prerequisites
- Python 3.8+
- `pip` (Python package manager)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/zaralrubaie/pre_trained-bot.git
cd nino-chatbot

Contact:
Zahraa— engzahra0083@gmail.com
GitHub: zaralrubaie
