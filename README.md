# 🚀 Fantom Bot  
### **A Multi-Agent AI Assistant with Web Search + PDF Tools**  
**Created by Soheil & Ghazal**  
Live Telegram Bot → **@FAntoMM1_bot**

---

## 📌 Overview  
Fantom Bot is a hybrid AI system that **combines Google ADK agents** with **local Python tools** to create a unified, ethical, and tool-aware assistant.  
It performs **web search**, **reasoning**, **memory**, and **PDF management** for each user through a consistent multi-agent architecture.

This project demonstrates how to align two incompatible worlds:  
- 🌐 *Cloud agents* (Selector Agent, Search Agent, memory, compaction)  
- 💾 *Local utilities* (PDF listing, merging, user-scoped directories)  

Fantom Bot is fully deployed on Telegram and serves real users.

---

## 🎯 Problem Statement  
Most chatbots can either think or act — but not both.  
They struggle to combine **real-time web intelligence** with **local file operations**, and they lack personalization, memory, and ethical behavior.

Fantom solves this by building an assistant that can:
- Answer conceptual questions  
- Retrieve fresh internet info  
- Manage user PDF files  
- Maintain session memory  
- Behave consistently and truthfully  

---

## 🧠 Why Agents?  
Agents allow modular, scalable behavior:
- **Selector Agent** chooses the right tool or sub-agent  
- **Search Agent** performs real Google-style search  
- **PDF Tools Agent** handles real files  
- **Persistent session memory** keeps the assistant consistent  
- **Compaction** prevents memory bloat  

Instead of one big model, Fantom is a **team of specialists**.

---

## 🏗 Architecture  



- **Selector Agent** orchestrates everything  
- **Search Agent** handles up-to-date information  
- **Local PDF tools** work per-user  
- **Session Service (SQLite)** stores long-term memory  
- **Telegram layer** connects users globally  

---

## 🎬 Demo  
- “Search for the latest news…” → Search Agent  
- “What PDFs do I have?” → list_user_pdfs  
- “Merge them” → merge_user_pdfs  
- “Explain this concept…” → Selector answers directly  
The same logic powers the live Telegram deployment.

---

## 🛠 Build Details  
**Technologies Used:**
- Google **ADK** (LlmAgent, Runner, AgentTool, compaction)  
- **Gemini 2.5 Flash**  
- Python (`pypdf`, `asyncio`, `sqlite+aiosqlite`)  
- Custom user state management  
- Telegram Bot API for deployment  

---

## 🚧 If I Had More Time  
- Add OCR and text extraction for PDFs  
- Deploy a web UI with real-time streaming  
- Background workers for heavy tasks  
- Image tools (PDF → PNG, summarization)  
- Advanced analytics for agent memory  

---

## ✨ Summary  
Fantom is a practical example of **multi-agent AI engineering**:  
an ethical assistant that can search, reason, remember, and manipulate files—running smoothly in both a notebook environment and a live Telegram bot.
