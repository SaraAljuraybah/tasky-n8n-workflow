# Tasky 🤖

Tasky is a simple Telegram task manager bot built using **n8n**.

You can send tasks to the bot and ask for:
- Today's tasks
- This week's tasks
- This month's tasks

All tasks are stored in Google Sheets and each user only sees their own tasks.

---

## Features
- Telegram bot integration
- Add tasks using a simple format
- Daily / weekly / monthly views
- Supports multiple users
- Uses Google Sheets as a database

---

## How it works
- Telegram Trigger listens to messages
- Commands are handled using a Switch node
- Tasks are stored and read from Google Sheets
- A single JavaScript node formats results for `/today`, `/week`, and `/month`

---

## Getting Started
1. Import the workflow JSON into n8n
2. Set up your Telegram Bot token
3. Connect Google Sheets credentials
4. Publish the workflow

---

## Notes
- This project was built for learning and experimentation
- Feel free to fork and customize ✨

![n8n Workflow](https://raw.githubusercontent.com/SaraAljuraybah/tasky-n8n-workflow/refs/heads/main/tasky-n8n-workflow.png)
