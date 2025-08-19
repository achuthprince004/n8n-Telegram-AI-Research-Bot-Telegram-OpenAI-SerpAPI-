# 📡 AI Research Assistant (Telegram + OpenAI + SerpAPI)

## 🚀 Overview
This project is an **AI-powered research assistant** built using **n8n** 
It integrates **Telegram**, **OpenAI**, and **SerpAPI** to provide real-time, structured, and user-friendly answers directly in a Telegram chat.

- 📲 **Telegram** – Interface for user queries and responses  
- 🤖 **OpenAI** – Processes and organizes results into concise summaries  
- 🔎 **SerpAPI** – Fetches **real-time search results** (titles, snippets, prices, links, images)  
- 🌐 **ngrok** – Exposes local n8n workflows to the internet as a secure server  

---

## ✨ Features
- ✅ Real-time web search powered by **SerpAPI**  
- ✅ AI summarization & formatting with **OpenAI**  
- ✅ Seamless chat-based interaction via **Telegram Bot**  
- ✅ Integrated with **Telegram, OpenAI, and SerpAPI** APIs  
- ✅ ngrok tunnel for running n8n locally and exposing it as a server     

---

## 📂 Project Structure
- `Telegram Trigger` → Captures messages from Telegram  
- `Research AI Agent` → Analyzes queries using OpenAI + SerpAPI  
- `SerpAPI` → Retrieves search results  
- `OpenAI Chat Model` → Summarizes & formats results  
- `Send Message` → Sends the final response back to Telegram  
- `ngrok` → Creates a public HTTPS URL for Telegram webhook integration 
---

## 🙌 Author

**Achuth Akilesh**  
Product Designer & Data Analyst  
🌐 [Portfolio Website](https://madebyachuth.framer.website/)
