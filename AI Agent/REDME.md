# 📅 WhatsApp AI Booking Agent (n8n Blueprint)

An intelligent AI Agent blueprint for automated scheduling via WhatsApp. Built with **n8n**, this workflow seamlessly integrates your calendar, database, and AI into one powerful.

---

## ✨ Key Features

* 💬 **Natural WhatsApp Interaction:** Powered by **Evolution API** for a human-like chat experience.
* 📅 **Real-time Google Calendar Sync:** Automatically checks for free slots, avoiding overlaps and double bookings.
* 📊 **Automatic Logging:** Confirmed bookings are instantly saved to **Excel/Google Sheets** for tracking and CRM.

---

## 🛠️ Tech Stack

* **Orchestration:** [n8n](https://n8n.io/)
* **AI Engine:** OpenAI (GPT-4o)
* **Messaging:** [Evolution API](https://evolution-api.com/) (WhatsApp)
* **Calendar:** Google Calendar API
* **Database:** Excel / Google Sheets

---

## 📋 Requirements

Before importing the workflow, ensure you have the following ready:

1.  **n8n Instance:** Self-hosted (Docker).
2.  **Evolution API:** A running instance connected to a WhatsApp number.
3.  **OpenAI API Key:** For the AI Agent and RAG capabilities.
4.  **Google Credentials:** OAuth2 credentials for **Google Calendar** and **Google Sheets**.
5.  **Data Table:** An Excel or Google Sheets file containing your services, descriptions, and prices.

---

## 🚀 Quick Start

1.  **Download** the `workflow.json` file from this repository.
2.  In your **n8n** dashboard, click on **Import from File** and select the JSON.
3.  **Configure Credentials:** Update the nodes with your own OpenAI, Evolution API, and Google account details.
4.  **Knowledge Base:** Point the "Search_Data_Table" node to your specific Excel/Google Sheets file.
5.  **Activate:** Switch the workflow to **Active** and start booking!

---


## 🤝 Let's Connect

If you found this workflow useful, feel free to give this repository a ⭐!
---
