# 🧠 Simple LangChain Chatbot 🤖

Welcome to this **beginner-friendly tutorial** on building a chatbot using **LangChain** and **LangGraph** by Drishya!  
This project demonstrates how to create a conversational AI bot using **Google Gemini AI**.

---

## Features

- Interactive AI chatbot using LangChain + LangGraph  
- Uses **Google Gemini AI** as the language model  
- Simple conversation flow: `START → chatbot → END`  
- Step-by-step guide for beginners in Colab or Jupyter Notebook

---

## Prerequisites

- A Google account and API key (instructions below)  
- Python 3.x (for local setup)  

---

## Getting Your Google API Key 🔑

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)  
2. Sign in with your Google account  
3. Click **Create API Key**  
4. Copy the key and **keep it safe**  

> ⚠️ Never share your API key publicly or commit it to GitHub.

---

## Installation

### Option 1: Run in Google Colab (Recommended for Beginners)

- Open the notebook `langchain_chatbot_simple.ipynb`  
- Run the `%pip install` cell at the top to install all required packages  
- Set your API key using the provided cell  

### Option 2: Run Locally with `requirements.txt`

1. Clone the repository:

```bash
git clone https://github.com/drishyashrestha/Simple-Langchain-Chatbot.git
cd Simple-Langchain-Chatbot
```
2. Install all dependencies:
```bash
pip install -r requirements.txt
```
3. Set your Google API key in your environment:
```python
export GOOGLE_API_KEY="your_api_key_here"  # Linux / macOS
set GOOGLE_API_KEY="your_api_key_here"     # Windows

```
Open the notebook in Jupyter and run all cells.

## How to Use

Test examples:
```python
send_message("What is LangChain simply?")
send_message("Can you explain Python in simple terms?")
send_message("Write a short poem about robots learning to code")
```

### Interactive chat mode:

Run the interactive cell and type your messages.

Type "quit" to exit the chat.



## Resources

[LangChain Documentation](https://docs.langchain.com/oss/python/langchain/overview)

[LangGraph Documentation](https://docs.langchain.com/oss/python/langgraph/overview)

[Google AI Studio](https://aistudio.google.com/)



## License

This project is open-source and free to use for learning purposes.
