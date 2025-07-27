# 🦜 LangChain SQL Chatbot using Streamlit

This project is a **ChatGPT-like interface** built using **LangChain**, **Streamlit**, and **GROQ's LLaMA3 model**, allowing users to **chat with their database using natural language**. It supports:
- **SQLite** (default: `student.db`)
- **MySQL** (user-configurable)

---

## 🚀 Features

- 🔌 Connect to either a local **SQLite3** database or a **MySQL** database
- 🧠 Ask natural language questions and get intelligent SQL-backed answers
- 🗃️ Uses **LangChain SQL Agent** to parse your questions into SQL queries
- 🧵 Maintains chat history using Streamlit’s `session_state`
- 🦙 Powered by **GROQ's LLaMA3-8B-8192** model (via API)

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
