🍽️ WhatsApp Food Ordering Bot

An AI-powered **WhatsApp food ordering assistant** built using **n8n**, **Groq LLM**, and **Google Sheets**.
The bot allows users to check menu availability, place orders, and get instant responses — all through WhatsApp.


🚀 Project Overview

This project demonstrates how **workflow automation + LLMs** can be used to build a real-world conversational system.

Users can:

* Interact using **natural language or numbered options**
* Check food availability in real time
* Place confirmed orders
* Get FAQs like delivery time and payment methods

All responses are clean, human-like, with no backend or tool logic exposed.


✨ Key Features

* 📱 WhatsApp-based conversational interface
* 🤖 AI Agent powered by Groq (LLaMA 3.1)
* 📦 Real-time inventory check from Google Sheets
* 🧾 Order confirmation & storage
* ℹ️ FAQ handling (delivery time, payment, hours)
* 🔒 Secure setup (no credentials exposed)


🧠 Architecture
Workflow:

```
WhatsApp Trigger
   ↓
AI Agent (Groq Chat Model)
   ↓
Tools
   ├── Dishes (Inventory Check)
   ├── FAQ (Information)
   └── Order (Save Confirmed Orders)
   ↓
WhatsApp Response
```


🛠️ Tech Stack

* **n8n** – Workflow automation
* **Groq LLM** – LLaMA 3.1 chat model
* **Google Sheets** – Inventory, FAQ, Orders
* **WhatsApp Cloud API** – User interaction

🧪 How It Works

1. User sends a message on WhatsApp
2. AI Agent understands intent (order / check / FAQ)
3. Relevant tool is triggered silently
4. Response is generated in plain text
5. Confirmed orders are saved automatically
   

📂 Repository Contents

```
workflow/
 └── whatsapp-food-ordering-bot.json
screenshots/
README.md
.gitignore
```

> ⚠️ API keys, credentials, and tokens are **not included**.



## ▶️ How to Run Locally

1. Import the workflow JSON into **n8n**
2. Configure credentials:

   * Groq API
   * WhatsApp Cloud API
   * Google Sheets
3. Activate the workflow
4. Start chatting via WhatsApp



 🎯 What This Project Demonstrates

* Practical use of **LLMs in automation**
* Tool-based AI agent design
* Clean prompt engineering
* Error handling and schema validation
* Production-style workflow thinking



👩‍💻 Author

Madhumita S M
B.Tech – Computer Science & Engineering
Interested in AI, automation, and real-world system design


Just tell me 💙
