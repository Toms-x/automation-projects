# Personal AI Assistant
 – Built with n8n, OpenAI & Telegram

This project is a Personal AI Assistant powered by n8n, integrating Telegram, OpenAI, and multiple productivity tools to streamline your digital tasks. The assistant communicates with you via Telegram and can read emails, manage your calendar, send messages to your contacts, and interact with databases. It functions as a centralized command center for your personal productivity.

---

## What It Can Do

This isn't just a chatbot — it's your productivity co-pilot:

- 📩 **Reads your emails** and gives you summaries  
- 🗓️ **Creates and fetches calendar events**  
- 📤 **Sends emails** with simple prompts  
- 👥 **Looks up your contacts** and messages them  
- 🧠 **Summarizes & updates databases**  
- 💬 **All through Telegram**

Built with the marketer (and curious automator) in mind. The goal? Free your hands so you can focus on what actually matters — thinking big, creating cool stuff, or just relaxing.

---

## How It Works

Here’s the basic flow (check the diagram in the repo):

1. **Telegram Trigger** – Listens to messages you send your bot  
2. **AI Agent (Tools Agent)** – Figures out what you want  
3. **OpenAI Chat Model** – Understands your intent  
4. **Tool integrations** – Executes stuff like sending emails, reading calendars, updating databases, etc.  
5. **Response** – Telegram sends you a reply like magic 💬✨

---

## ⚙️ What’s Under the Hood?

| Node                | What It Does                                |
|---------------------|----------------------------------------------|
| `Telegram Trigger`  | Starts the workflow when you send a message |
| `AI Agent`          | Main brain – routes your message to tools   |
| `OpenAI Chat Model` | Makes sense of your request in plain English|
| `sendMessage`       | Replies to you on Telegram                  |
| `get_emails`        | Pulls in your recent emails                 |
| `send_emails`       | Sends emails for you                        |
| `set_calendar`      | Adds calendar events                        |
| `get_calendar`      | Shows your upcoming schedule                |
| `contacts`          | Looks up or messages your contacts          |
| `summarize database`| Gives you insights from stored data         |
| `update database`   | Edits database entries                      |

---

## Use Cases

- *“Add a call with Sarah to my calendar for Friday at 10am.”*  
- *“Send an email to John about the new campaign.”*  
- *“Summarize last week’s lead data from the database.”*  
- *“Read my latest emails and tell me what I missed.”*

---

## Getting Started

**You’ll need:**

- An n8n instance (self-hosted or cloud)
- A Telegram bot (create one via [BotFather](https://t.me/botfather))
- OpenAI API key
- Optional: Gmail, Google Calendar, database access

**Setup:**

1. Clone or import this workflow into n8n  
2. Connect the Telegram bot  
3. Add credentials for OpenAI, email, calendar, and database  
4. Hit activate and start chatting!

---

## 🧑‍💻 Why I Built This

I’m obsessed with **automation, AI, and marketing workflows**. I wanted a tool that lets me run my day through Telegram, from sending emails to updating CRMs and databases, without needing to bounce between apps.

This project brings together my love for natural language processing, no-code tools, and doing more with less. If you’re in marketing or operations, this setup could save you **hours** each week.

---

## Let's Connect

If this inspires you, or you build something cool with it — I’d love to see it.  
Feel free to fork, remix, or reach out.

Made with ☕, late nights, and lots of “wait, can I automate this too?” moments.
