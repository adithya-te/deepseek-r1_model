# 🔥 DeepSeek R1 AI Apps

Hey there! 👋  
This is a little project I built using **LangChain**, **Streamlit**, and **Ollama's DeepSeek models**.  
It has two cool AI-powered apps:

- 🧠 **DeepSeek Code Companion** — an AI coding buddy that helps you debug, explain code, and design solutions.
- 📘 **DocuMind AI** — a document assistant where you can upload PDFs and ask questions about them using RAG (Retrieval-Augmented Generation).

---

## 🚀 Live Demo Links

Wanna see it in action? Check these out:

- 🧠 **Code Companion** → [Try it here](https://adithya-te-deepseek-r1-model-app-t1xrax.streamlit.app/)
- 📘 **DocuMind AI** → [Try it here](https://adithya-te-deepseek-r1-model-rag-deep-qgrquy.streamlit.app/)

---

## 📂 What’s Inside

- `app.py` → Code Companion chatbot  
- `rag_deep.py` → DocuMind AI (PDF chat)  
- `requirements.txt` → All the Python packages you’ll need  

---

## 💻 How to Run This Locally

Wanna run it on your machine? Follow these steps:

### 1️⃣ Install Ollama  
Go grab it from 👉 [https://ollama.ai/](https://ollama.ai/)  

Then start the Ollama server:
```bash
ollama serve
And pull the models:
ollama pull deepseek-r1:1.5b
ollama pull deepseek-r1:3b
pip install -r requirements.txt

streamlit run app.py

streamlit run rag_deep.py

