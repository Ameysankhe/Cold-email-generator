# 📧 Cold Email Generator

A smart **cold email generator** built with **Groq, LangChain, and Streamlit**.  
This tool helps services companies quickly generate **personalized cold emails** targeted at companies that are actively hiring.  

## 🚀 Features

The app allows users to:
1. **Input the URL** of a company's careers page.  
2. **Extract job listings** from the page.  
3. **Generate personalized cold emails** tailored to the specific job descriptions.  
4. **Attach relevant portfolio links** automatically, sourced from a **vector database**, to strengthen the pitch.  

This saves **time for business development executives** while making outreach more relevant and impactful.

---

## 🛠️ Tech Stack

- [Groq](https://groq.com/) – Fast LLM inference  
- [LangChain](https://www.langchain.com/) – Orchestration & chaining logic  
- [Streamlit](https://streamlit.io/) – Interactive UI  
- [Vector Database (Chroma)] – Store and retrieve portfolio links  

## 📦 Installation

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/Ameysankhe/Cold-email-generator.git
cd Cold-email-generator
```

2️⃣ **Create & Activate Virtual Environment**  
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```

4️⃣ **Set Up Environment Variables**  
Create a `.env` file in `config/` with your Groq API key:  
```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the Streamlit app:  
```bash
streamlit run main.py
```

