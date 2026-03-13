# 🗓️ AI Scheduling Agent — n8n

An agentic AI workflow that listens for chat messages and automatically
creates Google Calendar events using natural language.



## 🧩 Components

- **Trigger**: When chat message received
- **AI Agent**: Core reasoning engine that interprets the message
- **Google Gemini Chat Model**: LLM powering the agent
- **Simple Memory**: Retains conversation context across messages
- **Google Calendar**: Creates events based on the chat input

## 💬 Example Usage

> "Schedule a meeting with the team tomorrow at 3pm"

The agent will parse the message and automatically create the event
in your Google Calendar — no manual input needed.

## 🚀 How to Use

1. Import `workflow.json` into your n8n instance
2. Add credentials:
   - Google Gemini API key
   - Google Calendar OAuth2 credentials
3. Activate the workflow
4. Open the chat and describe an event to schedule!

## 🛠️ Built With

- [n8n](https://n8n.io) — Workflow automation
- [Google Gemini](https://ai.google.dev) — LLM
- [Google Calendar API](https://developers.google.com/calendar) — Event creation
- n8n Simple Memory — Conversation history

## 📁 Files

| File | Description |
|------|-------------|
| `workflow.json` | Exported n8n workflow |
| `workflow.png` | Workflow diagram screenshot |

## 👩‍💻 Author

**Satya** — [LinkedIn](https://linkedin.com/in/satyeabattu)
