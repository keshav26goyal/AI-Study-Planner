🤖 AI Study Planner (n8n + OpenAI + Telegram)
An AI-powered study planner that automates planning, tracking, and updating study progress using Telegram, OpenAI, and Google Sheets.

🚀 Features
	•	📩 Telegram-based interaction
	•	🧠 AI intent classification
	•	📊 Google Sheets integration
	•	🔄 Auto update of study progress
	•	❓ Asks reason if study < planned
	•	✅ Marks tasks as completed

🧱 Tech Stack
	•	n8n
	•	OpenAI API
	•	Telegram Bot
	•	Google Sheets

⚙️ Workflow Overview
	1	User sends message via Telegram
	2	Intent classified using AI
	3	Subject & hours extracted
	4	Google Sheet updated
	5	If less hours → ask reason
	6	Final confirmation sent

￼📂 Setup Instructions
	1	Import workflow.json into n8n
	2	Add credentials:
	◦	Telegram Bot
	◦	OpenAI API Key
	◦	Google Sheets
	3	Run workflow
	4	Start chatting

🧠 Example Commands
	•	I studied DBMS for 2 hours
	•	I completed ACN
	•	Reason for DBMS: I was tired

👨‍💻 Author
Keshav Goyal
