# 💬 SQL Chat Assistant

**SQL Chat Assistant** is a Streamlit-based application that lets you query your database using natural language. Powered by LangChain and Groq's LLaMA3 models, this tool translates human questions into SQL queries and provides intelligent answers with just a few clicks.

## 🚀 Features

- 🤖 Ask natural language questions and get SQL-powered answers
- 🗂️ Supports both **SQLite** (`student.db`) and **MySQL** databases
- 🔐 Secure, on-the-fly Groq API key input (no hardcoding)
- 🔄 Remembers conversation history
- ♻️ Option to reset chat history
- ⚙️ Uses `LangChain` + `SQLDatabaseToolkit` for safe and dynamic query generation

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Groq LLaMA3](https://console.groq.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [SQLite3 / MySQL Connector](https://dev.mysql.com/doc/connector-python/en/)

## 📁 Project Structure
```bash
├── your_script.py            # Main Streamlit app
├── student.db                # (Optional) Sample SQLite database
├── requirements.txt          # Dependencies
└── README.md                 # You're here

