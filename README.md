🤖 AI Chatbot with n8n, OpenAI & SerpAPI
This project is a smart chatbot built using n8n, integrated with OpenAI for generating natural language responses and SerpAPI to fetch real-time web results. It takes user input, performs a web search, and responds with a well-structured, AI-generated answer—all within an automated workflow.

🚀 Features
🔍 Real-time web search using SerpAPI

🧠 Natural language processing with OpenAI

🔁 Fully automated chat and response flow via n8n

🧾 Clean and structured answers to user queries

⚙️ Technologies Used
n8n – Workflow automation platform

OpenAI API – For generating responses

SerpAPI – For real-time search results

📂 Folder Structure
pgsql
Copy
Edit
📁 n8n-chatbot/
├── README.md
├── workflows/
│   └── chatbot_workflow.json
📌 How It Works
User submits a query (e.g., "Tell me about Elon Musk").

The workflow triggers a SerpAPI call to search for relevant web content.

Results are passed to OpenAI to summarize and answer the query.

The final response is returned to the user.

📝 Setup Instructions
Clone this repo

Import the workflow into your n8n instance

Add API credentials for OpenAI and SerpAPI in n8n

Test via webhook or UI input
