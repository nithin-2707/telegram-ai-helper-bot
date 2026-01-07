# 🤖 Telegram AI Helper Bot (n8n + Gemini)

A real-time AI-powered Telegram bot built using **n8n** and **Google Gemini API**.
The bot automatically responds to user messages using AI without manual execution.

---

## 🚀 Features

- Real-time Telegram message handling
- AI-powered replies using Google Gemini
- Event-driven automation (no polling)
- Deployed on n8n Cloud
- No-code / low-code architecture

---

## 🧠 How It Works

1. User sends a message to the Telegram bot
2. Telegram Trigger captures the message
3. Message is sent to Gemini AI
4. AI generates a response
5. Bot replies instantly in Telegram

---

## 🛠 Tech Stack

- **Automation Platform:** n8n
- **Messaging:** Telegram Bot API
- **AI Model:** Google Gemini (gemini-2.5-flash)
- **Architecture:** Event-driven workflow

---

## 📂 Project Structure

```text
telegram-ai-helper-bot/
├── README.md
├── workflow/
│   └── n8n-telegram-ai-bot.json

