# Chatbot-Appointment-Scheduler-With-Google-Calendar-Telegram

<img width="768" height="440" alt="image" src="https://github.com/user-attachments/assets/40f87c7d-c830-4dd6-8532-18718d4a84b3" />




<img width="220" height="400" alt="image" src="https://github.com/user-attachments/assets/e97482e0-48da-406b-8496-c0b6104d6c10" />



<img width="220" height="400" alt="image" src="https://github.com/user-attachments/assets/c8df2732-6c26-4781-8831-f0ce0d33060e" />



<img width="220" height="400" alt="image" src="https://github.com/user-attachments/assets/1a671d74-792c-4f1b-be1f-a4de9978690d" />


# 🤖 Chatbot Appointment Scheduler with Google Calendar & Telegram (n8n)

## 📘 Overview
This project is an **AI-powered appointment scheduling chatbot** built using **n8n**, **Telegram Bot API**, and **Google Calendar**.  
It allows users to **book, confirm, and track appointments** directly through Telegram, with real-time availability checking and data logging in **Google Sheets**.

🧠 The assistant intelligently interacts with patients, checks Dr. Pulin’s calendar, and logs confirmed appointments — ensuring smooth scheduling automation.

---

## 🚀 Features

| Feature | Description |
|----------|-------------|
| 💬 **Telegram Chatbot** | Accepts appointment requests and interacts with patients conversationally. |
| 🧠 **AI Agent (LangChain)** | Manages logic for booking, slot checking, and user confirmations. |
| 📅 **Google Calendar Integration** | Checks availability and creates confirmed appointments automatically. |
| 📊 **Google Sheets Integration** | Logs appointment details (name, number, date, time). |
| 🪣 **Session Memory** | Maintains context across multiple chat exchanges. |
| 🧩 **n8n Modular Design** | Easy to customize or extend with more nodes (email, CRM, etc.). |

---

## 🧭 Workflow Overview

### 🧩 Nodes Used

| Node | Function |
|------|-----------|
| **Telegram Trigger** | Receives messages from Telegram users. |
| **AI Agent (LangChain)** | Core logic with booking prompt and rules. |
| **OpenAI Chat Model** | Uses GPT model (`gpt-4o-mini`) for natural conversation. |
| **Window Buffer Memory** | Maintains user session context. |
| **Google Calendar Tool (Check & Create)** | Verifies and books available appointment slots. |
| **Google Sheets Tool (Append Confirmed)** | Logs confirmed appointments. |
| **Telegram Send Message** | Sends back AI responses and confirmations to users. |

---

## 🧠 Prompt Logic (Core AI Instructions)
The AI Agent follows this defined role:

> 🎯 **Role of the Assistant:**  
> You are an AI assistant helping Dr. Pulin manage patient consultations.

---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites
- n8n (self-hosted or cloud)
- OpenAI API key
- Google Calendar API credentials
- Google Sheets API credentials
- Telegram Bot (via @BotFather)

📈 Data Flow Summary
| Step | Action                                | Tool                  |
| ---- | ------------------------------------- | --------------------- |
| 1    | User sends appointment request        | Telegram Trigger      |
| 2    | AI processes request and checks logic | LangChain AI Agent    |
| 3    | Slot verified                         | Google Calendar Tool  |
| 4    | Appointment logged                    | Google Sheets Tool    |
| 5    | Confirmation sent                     | Telegram Send Message |

🧰 Tech Stack

n8n (Workflow Automation)

LangChain (AI logic orchestration)

OpenAI GPT (Conversational intelligence)

Google Calendar API (Scheduling)

Google Sheets API (Record keeping)

Telegram Bot API (User interaction)

👨‍💻 Author

Developed by: Pulin
Role: IT & AI Engineer | Automation Specialist
💬 “Empowering workflows through practical AI automation.”

IT service delivery leader with 20+ years across incident, change, and problem management, PSA/RMM operations (ConnectWise), and endpoint security. Designs and operates Service Desk workflows with SLA rigor, and builds support automations using n8n, LLMs, and vector search for policy-aligned responses.
Leads Service Desk operations: ticket triage, scheduling, vendor coordination, SLA governance, and reporting.
Builds LLM-powered assistants on Telegram with strict topic guardrails and end-of-conversation flows.
Implements RAG pipelines: Google Drive ingestion, OpenAI embeddings (512-dim), Pinecone indexing, and chunking strategies for retrieval quality.
Experienced with ESET/SentinelOne endpoints, Microsoft stack, AWS (Solutions Architect), and ITIL-based practices for change/incident/request management.

Links

GitHub: https://github.com/Pulin2411

LinkedIn: linkedin.com/in/pulin-shah-741212b

Email: pulin2411@gmail.com

