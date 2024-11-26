# Gazzi Chatbot

Chatbot using Streamlit and Ollama for Windows

## Clone the Git repository
```
git clone https://github.com/dlawodud/gazzi-chatbot.git
cd gazzi-chatbot
```

## Create a Python virtual environment
```
python -m venv ./venv
```

## Activate the virtual environment
```
.\venv\Scripts\activate.ps1
```

## Install the dependencies
```
pip install streamlit langchain langchain_community
```

## Install Ollama

https://ollama.com/download

## Download the model
```
ollama pull gemma2:2b
```

## Run the Streamlit application
```
streamlit run app.py
```
