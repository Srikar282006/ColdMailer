# 📧 Cold Email Generator (AI-Powered)

An AI-powered application that generates highly personalized cold emails using LLMs and vector search. It uses your portfolio data and contextual inputs to craft targeted outreach emails for job applications, networking, or business leads.

---

## 🚀 Features

- ✨ AI-generated personalized cold emails
- 📂 Portfolio-based customization
- 🔍 Semantic search using ChromaDB
- ⚡ Fast response with LLM (Groq/OpenAI)
- 🧠 Context-aware email generation
- 🔐 Secure API key handling with `.env`

---

## 🛠️ Tech Stack

- **Python**
- **LangChain**
- **ChromaDB** (Vector Database)
- **LLM APIs (Groq / OpenAI)**
- **Streamlit** (optional UI)

---

## 📁 Project Structure
ColdMailer/
│
├── app.py # Main application entry point
├── chains.py # LLM chain logic
├── portfolio.py # Portfolio loading & processing
├── utils.py # Helper functions
├── my_portfolio.csv # Portfolio dataset
│
├── vectorstore/ # ChromaDB storage
│ ├── chroma.sqlite3
│ └── (index files)
│
├── .env # API keys (DO NOT COMMIT)
├── .gitignore # Ignored files
├── requirements.txt # Dependencies
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/ColdMailer.git
cd ColdMailer
run :- streamlit run app.py
