# 🚀 MCA Insights Engine

### 🧠 AI-Powered Assistant for Ministry Of Coperative Affairs Company Data Analysis

The **MCA Insights Engine** is an AI-driven tool that helps users interact with and analyze Ministry of Corporate Affairs (MCA) company data effortlessly.  
It combines **data cleaning, merging, and interactive AI-based querying** using **Google Gemini** and **LangChain** to deliver intelligent insights.

---

## 📂 Project Overview

This project demonstrates the integration of:
- Data preprocessing using **Pandas** and **NumPy**
- AI-powered chatbot responses using **Google Gemini API**
- Streamlit-based user interface for seamless interaction

---

## ⚙️ Features

✅ Clean and merge MCA datasets  
✅ Query company information using natural language  
✅ Gemini-powered intelligent responses  
✅ LangChain integration for structured prompt pipelines  
✅ Interactive Streamlit web app  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | Streamlit |
| **Backend** | Python |
| **AI/LLM** | Google Gemini (via langchain_google_genai) |
| **Data Handling** | Pandas, NumPy |
| **Version Control** | Git & GitHub |

---

## 🏗️ Folder Structure

MCA-Insight-Engine/
├── Data/
│   ├── Change logs/
│   │   ├── file1
│   │   ├── file2
│   │   └── ...
│   ├── Cleaned Data/
│   │   ├── file1
│   │   ├── file2
│   │   └── ...
│   ├── Enriched/
│   │   ├── file1
│   │   ├── file2
│   │   └── ...
│   ├── Master Data/
│   │   ├── file1
│   │   ├── file2
│   │   └── ...
│   ├── Simulated Snapshots/
│   │   ├── file1
│   │   ├── file2
│   │   └── ...
│   └── raw/
│       ├── file1
│       ├── file2
│       └── ...
├── Video/
│   ├── file1
│   ├── file2
│   └── ...
├── Scripts/
│   ├── file1
│   ├── file2
│   └── ...
└── README.md

---

## 🚀 How to Run

1️⃣ **Clone the Repository**
   ```bash
   git clone https://github.com/<ARD-droid>/MCA-Insight-Engine.git
   cd MCA-Insight-Engine
   ```

2️⃣  Install Dependencies

 ```bash
!pip install streamlit pyngrok google-generativeai pandas altair langchain langchain-openai langchain-google-genai 
 ```
3️⃣ Add your API Key

 ```bash
genai.configure(api_key="YOUR_GOOGLE_GEMINI_API_KEY")
 ```
4️⃣ Run your dashboard

```bash
!streamlit run /content/MCA-Insight-Engine/scripts/MCA-Dashboard.py --server.port 8501 & npx localtunnel --port 8501
 ```
## 💬 Example Questions for Chatbot

Try asking the MCA Assistant:

🏢 “How many new companies were registered?”

📅 “Show active companies only.”

📊 “Give a summary of registration by status.”

💼 “List some sample company names.”

🤔 “What does CIN mean?”

## 👨‍💻 Author
Abhay Raj Dixit
- Data Science Enthusiast | AI Developer
- 📧 dixitabhayraj2603@gmail.com
- 🔗 GitHub: https://github.com/ARD-droid
