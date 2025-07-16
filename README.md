> [!NOTE]  
> This is to Showcase Demo of the Product for buying and my Skillset

# 🛒 AI-Powered Price Tracker

A full-stack AI-enhanced product tracker that scrapes real-time listings, summarizes them using LLMs (via Groq), and displays results through a clean React frontend.

Built by a solo developer. Powered by real engineering, DevOps, and AI integrations.

---

## 🚀 Features

- 🔎 **Real-Time Scraping:** Collects product listings from e-commerce sites and custom Bing search using Puppeteer.
- 🤖 **AI Summarization:** Uses **Groq-hosted LLMs** (`LLaMA 4 Scout`, `Mixtral`, etc.) to summarize the best results per user query.
- 🌐 **Full Stack System:**
  - React + Vite frontend
  - Flask backend
  - MongoDB for storing queries
  - LangChain for model abstraction
- 🐳 **Containerized:** Fully Dockerized system via `docker-compose`.

---

## 🧠 Tech Stack

| Layer          | Technology                          |
|----------------|-------------------------------------|
| **Frontend**   | React, Vite, Axios                  |
| **Backend**    | Flask, LangChain, Python 3.12       |
| **AI Models**  | Groq API (`LLaMA`, `Mixtral`)       |
| **Scraping**   | Bing Search API, Puppeteer (Node.js)|
| **Database**   | MongoDB                             |
| **DevOps**     | Docker, Docker Compose              |

---


## Demo video 🎥


https://github.com/user-attachments/assets/24d5ddb6-f265-4400-870d-cd512b7a8c41


---

## Directory Structure 📁

```

├── ai-summariser
│   ├── ai_utils.py
│   ├── app.py
│   ├── Dockerfile
│   ├── prompt_template.txt
│   └── requirements.txt
├── backend
│   ├── config
│   │   └── db.js
│   ├── Controllers
│   │   ├── PromptController.js
│   │   └── UserController.js
│   ├── Dockerfile
│   ├── package-lock.json
│   ├── package.json
│   ├── Routes
│   │   ├── AuthRoutes.js
│   │   ├── GetPrice.js
│   │   └── SavePrompts.js
│   ├── Schemas
│   │   ├── PromptSchema.js
│   │   └── UserSchema.js
│   ├── Server.js
│   └── Validations
│       └── UserValidation.js
├── docker-compose.yml
├── frontend
│   ├── components.json
│   ├── Dockerfile
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── README.md
│   ├── src
│   │   ├── App.tsx
│   │   ├── components
│   │   │   ├── HistoryView.tsx
│   │   │   ├── InputResponse.tsx
│   │   │   ├── Sidebar.tsx
│   │   │   └── ui
│   │   │       ├── button.tsx
│   │   │       ├── card.tsx
│   │   │       ├── input.tsx
│   │   │       ├── separator.tsx
│   │   │       ├── sheet.tsx
│   │   │       ├── skeleton.tsx
│   │   │       └── tooltip.tsx
│   │   ├── hooks
│   │   │   └── use-mobile.tsx
│   │   ├── index.css
│   │   ├── lib
│   │   │   └── utils.ts
│   │   ├── main.tsx
│   │   ├── pages
│   │   │   ├── AuthPage.tsx
│   │   │   ├── ComingSoon.tsx
│   │   │   ├── DashBoard.tsx
│   │   │   └── LandingPage.tsx
│   │   ├── services
│   │   │   └── api.ts
│   │   ├── utils
│   │   │   └── decodeToken.ts
│   │   └── vite-env.d.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   └── vite.config.ts
└── README.md

```
