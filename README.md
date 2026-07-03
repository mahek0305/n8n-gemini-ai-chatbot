# 🤖 AI Chatbot using n8n & Google Gemini

A simple AI chatbot workflow built using **n8n** and **Google Gemini** with conversation memory support.

## ✨ Features

- AI-powered chatbot
- Google Gemini integration
- Conversation memory
- Easy to import into n8n
- Beginner-friendly workflow

---

## 🛠️ Tech Stack

- n8n
- Google Gemini API
- AI Agent
- Memory Buffer Window

---

## 📂 Workflow

The workflow consists of:

1. Chat Trigger
2. AI Agent
3. Google Gemini Chat Model
4. Simple Memory

The chatbot receives a message, sends it to Gemini, maintains conversation history, and returns a response.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repository.git
```

### 2. Import the workflow

Open n8n

Go to:

```
Workflows → Import from File
```

Select:

```
template2_sanitized.json
```

### 3. Configure Credentials

Create a new **Google Gemini API** credential inside n8n.

Replace the placeholder credential with your own.

### 4. Activate Workflow

Save the workflow and activate it.

---

## 📁 Project Structure

```
.
├── template2_sanitized.json
├── screenshots/
│   └── chatbot-workflow.png
└── README.md
```

---

## 📸 Workflow Screenshot

> Replace the image name below if yours is different.

```markdown
![Workflow](./screenchorts/workflow.png)
```

---

## 🔒 Security

This repository does **not** contain:

- API Keys
- Credential IDs
- Webhook IDs
- Instance IDs
- Sensitive configuration

All sensitive values have been removed before publishing.

---

## 📜 License

This project is licensed under the MIT License.
