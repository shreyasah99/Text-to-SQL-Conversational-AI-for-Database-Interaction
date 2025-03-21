

```markdown
# 💬 ChatWithSQL: Text-to-SQL Conversational AI for Database Interaction

🚀 [Live Demo](https://text-to-sql-conversational-ai-for-database-interaction-shreyas.streamlit.app/)

ChatWithSQL is a conversational AI tool that allows users to interact with a SQL database using **natural language**. Powered by **LLMs (Groq + LangChain)**, this app converts user questions into SQL queries, executes them, and returns human-readable answers — no SQL expertise required!

---

## 🔍 Features

- 🧠 **Natural Language to SQL**: Ask questions like "Show me all students with GPA above 8" — no need to write SQL manually.
- ⚙️ **LLM-Powered Translation**: Uses **Groq’s LLaMA3** model via LangChain to generate SQL queries.
- 🗃️ **SQLite Integration**: Works seamlessly with a sample `student.db` database.
- 🌐 **Streamlit UI**: Simple and interactive web interface.

---

## 🏗️ Tech Stack

| Technology     | Purpose                                  |
|----------------|-------------------------------------------|
| 🐍 Python       | Core language                            |
| 🧠 LangChain    | LLM orchestration                        |
| 🚀 Groq API     | Fast LLM responses (LLaMA3-8b)           |
| 🗃️ SQLite       | Lightweight relational database          |
| 🌐 Streamlit    | Web interface                            |
| 📦 dotenv       | Load environment variables securely      |


## 📁 Project Structure

```
├── app.py             # Main Streamlit interface
├── sqldata.py         # Database connection & query execution
├── student.db         # Sample SQLite database
├── .env               # (Optional) Your API keys (excluded from Git)
├── requirements.txt   # Python dependencies
└── README.md          # Project overview
```



## 📌 Deployment

Easily deploy on [Streamlit Cloud](https://streamlit.io/cloud).  
Set `app.py` as the **main file**, and configure `GROQ_API_KEY` under **Secrets**.

---

## 🙌 Acknowledgements

- [Groq](https://groq.com/)
- [LangChain](https://www.langchain.com/)
- [Streamlit](https://streamlit.io/)

---

## 👤 Author

**Shreyas Hingmire**  
📎 [Live App](https://text-to-sql-conversational-ai-for-database-interaction-shreyas.streamlit.app/)  
🌐 [LinkedIn](https://www.linkedin.com/in/shreyashingmire)

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

```

