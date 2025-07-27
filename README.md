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


🔐 API Key
You’ll need a GROQ API key to use the LLaMA3 model.

In the Streamlit sidebar, paste your GROQ API key:



.
├── app.py                # Main Streamlit app
├── student.db           # Sample SQLite DB
├── requirements.txt      # List of Python dependencies
└── README.md            # You're reading this!



How to Run
streamlit run app.py



🧪 Usage Instructions
Launch the app using streamlit run app.py

In the sidebar:

Choose between SQLite (default) or MySQL

Enter GROQ API key

If using MySQL, enter host/user/password/database

Start chatting! Example questions:

Show me all students with grade A

How many records are in the attendance table?



![app_main](https://github.com/user-attachments/assets/1825a360-bec7-4824-a197-e3f92886490f)

![result_2](https://github.com/user-attachments/assets/2936c562-627b-4c6a-86d7-60b46aea74cd)

![result_3](https://github.com/user-attachments/assets/a6a0d478-d109-4283-a9be-a867a6c06ea3)

![result_4](https://github.com/user-attachments/assets/4b68eb70-a895-40a6-9df5-8dea3479afbe)










