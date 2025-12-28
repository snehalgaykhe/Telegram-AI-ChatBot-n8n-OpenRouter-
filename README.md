# Telegram-AI-ChatBot-n8n-OpenRouter-
🤖 Telegram AI ChatBot (n8n + OpenRouter)  An AI-powered Telegram chatbot built using n8n workflow automation, OpenRouter LLM API, and Wikipedia integration. This bot can answer user queries in real time on Telegram by leveraging large language models and external knowledge sources.

<img width="1920" height="1080" alt="Screenshot 2025-12-23 145601" src="https://github.com/user-attachments/assets/c5ca9e4f-24f7-4160-94cb-73eb46b432f4" />

<img width="1920" height="1080" alt="Screenshot 2025-12-23 150135" src="https://github.com/user-attachments/assets/86c577cc-89c8-4fb4-b7bb-14d814f544e8" />

This project demonstrates how to build an intelligent Telegram chatbot using low-code automation (n8n).
The bot listens to user messages on Telegram, processes them using an AI agent powered by OpenRouter, optionally fetches factual data from Wikipedia, and sends accurate, human-like responses back to users.

🚀 Features

🤖 AI-powered responses using OpenRouter LLMs

📩 Real-time Telegram message handling

📚 Wikipedia integration for factual answers

🔄 Automated workflow using n8n

⚡ No backend coding required (low-code solution)

🌐 Cloud-hosted n8n workflow

🛠️ Tech Stack

n8n – Workflow automation platform

Telegram Bot API – User interaction

BotFather – Telegram bot creation

OpenRouter API – AI/LLM responses

Wikipedia API – Knowledge retrieval

Cloud n8n Instance – Workflow deployment

🧩 Workflow Architecture

Telegram Trigger

Listens for incoming messages from users

AI Agent (n8n)

Processes the user query

Uses OpenRouter Chat Model for AI responses

Uses Wikipedia tool when factual data is required

Send Message Node

Sends the generated response back to Telegram

🔑 Prerequisites

Telegram account

Telegram Bot Token (via BotFather)

OpenRouter API Key

n8n (Cloud or Self-hosted)

⚙️ Setup Instructions

Create a Telegram bot using BotFather

Get your Telegram Bot Token

Create an account on OpenRouter and generate an API key

Set up an n8n workflow with:

Telegram Trigger

AI Agent (OpenRouter model)

Wikipedia tool

Send Message node

Add API keys securely in n8n credentials

Activate the workflow 🎉

💡 Use Cases

AI learning assistant

Educational chatbot

Knowledge-based Q&A bot

Automation + AI demo project

Resume & portfolio project

📈 Future Enhancements

Conversation memory

Multi-language support

Custom knowledge base

User authentication

Analytics & logging

