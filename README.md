# sql_data_AI_chatbot_n8n
🤖 AI SQL Chatbot (n8n + Gemini + PostgreSQL)

Hi! I’m shiva and this is my AI-powered chatbot project, built using n8n, Google Gemini (you can use OpenAI too), and a live PostgreSQL (Supabase) database.

This bot can turn natural language questions into SQL, run them live on your database, and reply just like a human—with real business answers, clear tables, or just friendly chat!

✨ What This Project Does

Chat with your data: Ask questions like “How many orders were shipped last week?” or “Show me the top 5 customers.”

Smart SQL: The bot understands your question, creates the SQL, and runs it on your database instantly.

Human answers: It shows tables, summaries, or just talks like a real assistant, depending on what you ask.

Hybrid chat: If you just say “Hi” or “How are you?” it’ll respond like a normal chatbot.

🗂️ Files

Chatbot.json — The complete n8n workflow (import this into n8n)

README.md — This file

schema.sql` — SQL file with the full database schema (all tables/columns)

🚀 How To Use

Import the Workflow

Go to n8n → Workflows → “Import from File” → select Chatbot_copy.json.

Add Your API Keys

Set up Gemini (or OpenAI) API credentials in n8n.

Set up your PostgreSQL/Supabase connection.

Start Chatting

Use a webhook, chat UI, or trigger manually in n8n.

Try questions like:

“How many orders are pending?”

“Show all customers with lifetime value over $2,000.”

“List today’s shipments.”

Or just say “Hello!”

Customize if You Want

Tweak the AI prompts for your own database tables, add more logic, or connect to your favorite frontend.

💡 Example Use Cases

Real-time business reporting (sales, orders, customers)

Internal support/helpdesk bots

Analytics for e-commerce, SaaS, or operations teams

Fun data exploration for your own side projects

🧑‍💻 About Me

 @shivanandhareddy a data engineer and AI enthusiast, building modern, human-like bots for real business needs.

Feel free to fork, use, or contribute!If you use this bot, tag me or reach out on GitHub—I’d love to connect. 🚀

![image](https://github.com/user-attachments/assets/94b1e679-f78c-4a0e-a88b-d64e58658609)


