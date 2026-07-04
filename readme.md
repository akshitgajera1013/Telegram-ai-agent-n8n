# 🤖 Telegram AI Agent using n8n

Telegram AI Agent

n8n • Mistral AI • Tavily • Telegram • Render

An intelligent AI-powered Telegram chatbot built with **n8n**, **Mistral AI**, and **Tavily Search**.

The bot can:
- 💬 Chat naturally like ChatGPT
- 🌍 Search the Internet when needed
- 🧠 Remember previous conversations
- ⚡ Respond instantly on Telegram
- ☁️ Deploy easily on Render

---

# Features

- AI Agent powered by Mistral AI
- Telegram Bot Integration
- Tavily Internet Search
- Conversation Memory
- Production Ready Workflow
- Render Deployment
- Environment Variable Support

---

# Architecture

```
Telegram User
      │
      ▼
Telegram Trigger
      │
      ▼
AI Agent
      ├── Mistral Chat Model
      ├── Tavily Search Tool
      └── Simple Memory
      │
      ▼
Telegram Send Message
```

---

# Tech Stack

- n8n
- Telegram Bot API
- Mistral AI
- Tavily Search
- Docker
- Render

---

# Workflow

Import

```
workflow/telegram_ai_agent.json
```

into n8n.

---

# Setup

## Clone

```bash
git clone https://github.com/YOUR_USERNAME/Telegram-ai-agent-n8n.git

cd Telegram-ai-agent-n8n
```

## Create Telegram Bot

Create a bot using BotFather.

## Get API Keys

- Mistral AI
- Tavily AI

## Import Workflow

Import the JSON workflow into n8n.

## Configure Credentials

Add

- Telegram
- Mistral
- Tavily

credentials inside n8n.

Activate the workflow.

---

# Screenshots

## Workflow

(Add screenshot)

## Telegram Chat

(Add screenshot)

---


