MCA Insights Dashboard
Overview

The MCA Insights Dashboard is a web-based interactive dashboard built using Streamlit, Pandas, Altair, and Google Gemini AI.
It allows users to:

Explore MCA company data from enriched datasets.

Filter and search companies by CIN, name, and status.

View daily change logs with interactive visualizations.

Interact with an AI assistant for insights and questions about the dataset.

Features

Master Dataset Exploration: Filter, search, and view company details.

Daily Change Logs: Track new incorporations, deregistered companies, and field updates.

Visualizations: Interactive bar charts to show change trends over time.

AI Assistant: Ask questions about the dataset using Google Gemini AI (via the text-bison-001 model).

Ngrok Integration: Access the dashboard via a public URL for easy sharing.

Technologies Used

Python 3.12

Streamlit

Pandas

Altair

Google Generative AI (google-generativeai)

Pyngrok

Installation

Clone the repository

git clone <your-repo-url>
cd MCA-Insight-Engine


Install dependencies

pip install -r requirements.txt


or

pip install streamlit pyngrok google-generativeai pandas altair


Set up environment variable for Google API Key

export GOOGLE_API_KEY="your_google_gemini_api_key"

Running the Dashboard

Run the Streamlit app

streamlit run scripts/MCA-Dashboard.py


Access via Ngrok (if using Colab/remote machine)
The public URL will be printed in the console.

Usage

Use the search boxes to filter by CIN or company name.

Use the status multiselect to filter by company status.

View the daily summary of changes.

Ask the AI assistant questions about the dataset in the chat section.

File Structure
MCA-Insight-Engine/
│
├─ Data/
│   ├─ Enriched/
│   │   └─ enriched_sample.csv
│   └─ Change logs/
│       └─ *.csv
│
├─ scripts/
│   └─ MCA-Dashboard.py
│
├─ README.md
└─ requirements.txt

Example Questions for AI Assistant

"How many new companies were registered last month?"

"List 5 companies with status 'Active'."

"Which companies were deregistered in the last week?"

Author

Abhay Raj Dixit
Computer Science Student & Data Enthusiast
