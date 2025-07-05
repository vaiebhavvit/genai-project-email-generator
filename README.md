# 📧 Email Generator using Gen AI

A Generative AI-powered tool that helps software service companies (like TCS, Infosys, Attic Technologies, etc.) generate personalized cold emails by analyzing job descriptions from potential client portals. Built using LangChain, Streamlit, and LLaMA 3.3 70B Versatile via Groq.

---

## 🚀 Features

- 🔍 Accepts job descriptions (text or URL)
- 🧠 Extracts relevant skills and roles using `unstructured` and `pandas`
- ✉️ Generates cold emails tailored to the client's job post
- 🌐 Streamlit-based interactive interface
- 📎 Attaches relevant portfolio links
- ⚙️ Powered by `LLaMA 3.3 70B Versatile` via Groq & LangChain

---

## 🛠️ Tech Stack

| Tool/Library            | Purpose                                         |
|-------------------------|-------------------------------------------------|
| `langchain==0.2.14`     | LLM prompt chaining and orchestration           |
| `langchain-community`   | Community tools and integrations                |
| `langchain-groq`        | Connects to LLaMA 3.3 70B via Groq              |
| `chromadb`              | (Optional) vector memory storage                |
| `streamlit`             | Web UI framework                                |
| `pandas`                | Data processing and skill extraction            |
| `python-dotenv`         | Manages environment variables and API keys      |
| **Model**: LLaMA 3.3 70B Versatile | Used via Groq API for email generation |

---

## 📦 Installation

1. **Clone the repo**

```bash
git clone https://github.com/vaiebhavvats/genai-cold-email-generator.git
cd genai-cold-email-generator







Set up .env

Create a .env file in the root directory and add your Groq or LLM API key:

GROQ_API_KEY=your_api_key_here







Usage
Run the Streamlit app

bash
streamlit run app.py
Provide input

Paste a job description OR

Provide a job URL to scrape using Selenium + Unstructured

Get your email

The tool will extract key information and generate a cold email

Copy, edit, or attach your engineer portfolios as needed