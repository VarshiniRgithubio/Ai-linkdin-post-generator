# LinkedIn Auto Post Workflow (n8n)
📖 About

This workflow automatically creates and posts LinkedIn content using Google Sheets, Gemini AI, and the LinkedIn API.
When you add a new post title in your Google Sheet, the workflow generates a full LinkedIn post and publishes it automatically.

⚙️ How It Works

Google Sheets Trigger – Watches your Google Sheet for new rows or updates.

If Node – Checks if the status is "pending".

AI Agent (Gemini) – Takes the LinkedIn Post Title and generates an engaging post.

Code Node – Cleans the AI output and formats it properly.

LinkedIn API – Posts the generated content directly to your LinkedIn account.

🧾 Example Google Sheet
Linkedin Post Title	Status
AI in Modern Agriculture 🌾	pending
Future of Data Science 🚀	pending

When a new row is added with status pending, the workflow:
✅ Generates the post → ✅ Cleans it → ✅ Publishes it → ✅ Can be marked as posted later.

🧰 Tools Used

n8n for automation

Google Sheets for input

Google Gemini AI for post generation

LinkedIn API for publishing

👩‍💻 Created By

Varshini Ramesh
Automating LinkedIn post creation using AI + n8n 🚀
