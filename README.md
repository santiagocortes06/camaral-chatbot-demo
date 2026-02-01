# Camaral – AI Chatbot for Client Trust & Adoption

## 🎯 Objective
This project implements an AI-powered chatbot designed to help potential clients
understand Camaral’s value proposition, use cases, and benefits in a clear and
trust-building way.

The chatbot answers frequently asked questions and guides users toward relevant
actions such as requesting a demo.

---

## 🌐 Live Demo (Frontend)
The chatbot is available online via a Lovable-powered frontend:

👉 **Live Chatbot:**  
https://camaral-chat-spark.lovable.app

---

## 🧠 Architecture Overview
- **Frontend:** Lovable (AI-first UI builder)
- **Backend:** n8n (workflow orchestration)
- **LLM:** OpenAI Chat Model
- **Knowledge Base:** Markdown file hosted on GitHub
- **Integration:** REST Webhooks

---

## 🔁 How It Works
1. User interacts with the chatbot via the Lovable frontend
2. The message is sent to an n8n webhook
3. n8n:
   - Fetches the knowledge base from GitHub
   - Injects user input + context into the LLM
   - Generates a contextual response
4. The response is returned to the frontend in real time

---

## ✨ Features
- Natural language conversation
- Context-aware responses
- Dynamic knowledge base (updated from GitHub)
- Sales and support-oriented messaging
- Clear call-to-action (demo scheduling)
- Scalable and maintainable architecture

---

## 📚 Knowledge Base
The chatbot is powered by a Markdown-based knowledge base stored in this repository:

`/knowledge-base/camaral_kb.md`

This allows easy updates without modifying the workflow logic.

---

## ⚙️ n8n Workflow
The complete workflow used in this project can be found here:

`/n8n/workflow-camaral-chat.json`

---

## 📸 Demo Evidence
Screenshots showing the chatbot, workflow, and integrations are available in:

`/demo/screenshots/`

---

## 🚀 Author
Santiago Cortes Arias
