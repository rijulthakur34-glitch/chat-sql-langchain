# Q&A Chatbot (Streamlit + LangChain)

A simple question-answer chatbot built with Streamlit and LangChain.

## Setup

1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Create a `.env` file with your API keys (see below)
6. Run the app: `streamlit run app.py`

## Environment variables

Create a `.env` file in the project root (not included in the repo):

```
OPENAI_API_KEY=your_key_here
LANGCHAIN_API_KEY=your_key_here
```

## Ollama version

Run the local Ollama version with:

```
streamlit run 3-ollamachatbot/app.py
```
