⚡ Data Analyst Agent 2.0 — Your AI-Powered Data Companion

Smarter, faster, and more intuitive analysis of datasets using Generative AI + Python automation.
Note: This project is proprietary. You may view and use it for learning purposes, but you are not allowed to copy, reuse, or redistribute this project in any form.

📌 Overview

Meet Data Analyst Agent 2.0 — an AI-driven assistant that cuts through tedious data crunching.
Simply upload your dataset + questions, and instantly get:
✅ Interactive reports
✅ AI-generated insights
✅ Automated workflows

Ideal for:

Analysts 🧾

Researchers 🔬

Startups & Businesses 📈

Anyone who loves turning raw data into knowledge

✨ Features
Feature	Why It Matters 🚀
🤖 AI-Powered Insights	Google Generative AI interprets your data intelligently
📊 Beautiful Visuals	Auto-generates plots using Matplotlib & Seaborn
🌍 Web Scraping Mode	Fetch real-time data from the internet
📂 Multi-Format Support	Works with CSV, Excel, JSON, Parquet, and TXT
🔄 Batch Query Handling	Run multiple data questions at once
🖥️ Easy to Use	Beginner-friendly, zero steep learning curve
⚡ Optimized for Speed	Built for performance & real-time feedback
🚀 Quick Start
1️⃣ Clone the Repo
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent

2️⃣ Install Requirements
pip install -r requirements.txt

3️⃣ Configure API Keys

Create a .env file in the project root:

GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240

4️⃣ Run the App
python -m uvicorn app:app --reload


Open http://localhost:8000/
 in your browser 🌐

🧑‍💻 How It Works

Write your queries in a .txt file (e.g., Show revenue growth month-over-month, Find correlation between Age and Income, etc).

Upload both the dataset + questions file.

The agent will:

Process queries with AI

Generate insights & summaries

Build neat visualizations automatically

🛠 Tech Stack

Backend:

FastAPI ⚡ (high-performance API)

LangChain 🧠 (LLM orchestration)

Google Generative AI ✨ (AI reasoning)

Pandas + NumPy 📊 (data wrangling)

Seaborn + Matplotlib 🎨 (visuals)

Frontend:

HTML5, CSS, JavaScript

Bootstrap-styled modern UI

🔧 API Endpoints
Method	Endpoint	Description
GET	/	Access web UI
POST	/api	Submit dataset + queries
GET	/summary	Diagnostics & summaries
📂 Supported File Types
Format	Extensions
CSV	.csv
Excel	.xlsx, .xls
JSON	.json
Parquet	.parquet
Text	.txt
🎯 Use Cases

📈 Business strategy → sales, KPIs, forecasting

🔬 Research → hypothesis validation, data exploration

🤖 Data science → anomaly detection, quick EDA

📊 Reporting → automated dashboards

🔒 Security

✅ Data stays local (no cloud uploads)

✅ API keys protected via .env

✅ Configurable CORS for production

📜 License

This project is licensed under MIT.
⚠️ Important: You may not copy, clone, or redistribute this project as your own. Any unauthorized use, modification, or replication is strictly prohibited.
