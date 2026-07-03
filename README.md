# Chat SQL (Streamlit + LangChain)

A chatbot built with Streamlit and LangChain that allows you to chat with a SQL database using natural language. It uses Groq's Llama models and a zero-shot ReAct agent with tool calling to query your database dynamically.

## Features

- **Talk to your Database**: Ask questions in plain English and get answers directly from your SQL database.
- **Local SQLite Support**: Easily connect to a local SQLite database (like the provided `student.db`).
- **MySQL Support**: Connect to a remote MySQL database by entering your credentials in the sidebar.
- **Powered by Groq**: Uses lightning-fast Llama 3 models hosted on Groq for agentic reasoning.

## Setup

1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. (Optional) Create a dummy local SQLite database by running: `python sqlite.py`
6. Run the app: `streamlit run app.py`

## Usage

You can supply your Groq API key in the sidebar of the Streamlit app. If you don't have one, you can get it from [Groq Cloud](https://console.groq.com/).

To use a local database, ensure `student.db` is present in the directory. You can query tables like `STUDENT`.
