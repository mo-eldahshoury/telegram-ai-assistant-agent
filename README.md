# 🤖 Conversational Telegram AI Assistant with Memory (n8n & Gemini)

A context-aware automated Telegram Assistant built using **n8n**, powered by **Google Gemini LLM**, and enhanced with **Simple In-Memory** capabilities to retain context across user conversations.

## 🚀 Overview
This workflow functions as an intelligent AI bot on Telegram. Unlike standard stateless bots, it utilizes an **AI Agent Node** integrated with a **Simple Memory Node** to maintain short-term conversational context, allowing users to have fluid, multi-turn interactions.

## 🛠️ Tech Stack & Architecture
- **n8n** (Automation Engine)
- **Telegram Trigger & Bot API**
- **n8n AI Agent Node**
- **Google Gemini Chat Model**
- **Simple Memory Node** (Session History Management)

## 📂 Features
- **Context-Aware Responses:** Remembers previous user turns within the active session window.
- **Dynamic Webhook Execution:** Fires instantly upon receiving new Telegram messages.
- **LLM Integration:** Utilizes Google's Gemini Flash model for fast and accurate responses.

## 📦 How to Import
1. Download the `telegram-ai-assistant.json` file from this repository.
2. In your n8n workspace, click **Workflows** -> **Import from File**.
3. Add your **Telegram Bot API Credentials** and **Google Gemini API Key**.
4. Activate the workflow!

---
*Developed by Mohamed Abdelrahman*
