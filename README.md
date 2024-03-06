# Gemini-ChatBot

A Q&A chatbot `qachat.py` and a vision-bot `vision.py` using **Google's Gemini-Pro** API with a basic UI

**Q&A Chat-Bot** can answer questions that are asked and display the chat history.
**Vision-bot** can take a picture as input, answer questions based on it, and classify or describe the same

## Usage:
Firstly install required python libraries
```bash
pip install streamlit
pip install google-generativeai
pip install python-dotenv
```
NOTE:The API key used is available on Google's AI for developers(Gemini-Pro)

To run:
```bash
streamlit run qachat.py
streamlit run vision.py
```
