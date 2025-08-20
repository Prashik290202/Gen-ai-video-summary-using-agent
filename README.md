# Gen-ai-video-summary-using-agent
🎥 Multimodal AI Agent – Video Summarizer

An interactive Streamlit app powered by Phidata Agents + Google Gemini 2.0 Flash Exp that summarizes videos and answers user queries with context-aware insights. The agent uses multimodal AI capabilities and DuckDuckGo search for additional context.

🚀 Features

📂 Upload video files (.mp4, .mov, .avi)

🤖 Gemini 2.0 Flash Exp model for fast multimodal reasoning

🔍 Ask custom queries about the video (e.g., "Summarize the key points", "What topics are discussed?")

🌍 DuckDuckGo Search integration for supplementary web knowledge

🎯 Detailed, user-friendly, and actionable insights

🛠️ Tech Stack

Streamlit – UI for interaction

Phidata – AI Agent framework

Google Generative AI (Gemini) – Multimodal LLM

DuckDuckGo Search – Web research tool

dotenv – Environment variable management

Install dependencies
pip install -r requirements.txt

 Add API Key

Create a .env file in the project root:

GOOGLE_API_KEY="your_api_key_here"

▶️ Run the App
streamlit run app.py


Open browser at http://localhost:8501 🎉

📌 Example Usage

Upload a video (.mp4, .mov, .avi)

Enter your query in the text box

Example: “Summarize the discussion in this video”

Click Analyze Video

View AI-generated insights and summaries

📦 Requirements
phidata
python-dotenv
yfinance
packaging
duckduckgo-search
fastapi
uvicorn
groq
openai
sqlalchemy
pgvector
psycopg[binary]
pypdf
streamlit
google-generativeai

🌟 Future Enhancements

Support for YouTube video URLs

Multi-language transcription and summarization

Export summaries to PDF/Word/Markdown

📜 License

MIT License. Feel free to use and modify.

⚡ This project demonstrates how Agentic AI + Multimodal LLMs can provide intelligent video summarization for real-world use cases.
