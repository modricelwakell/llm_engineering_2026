# Week 1 – LLM Engineering


## 📅 Day 1: APIs & Multi-Model Interaction

### 🧠 Overview

Learned how to interact with different LLMs using APIs and built a simple system where two models talk to each other.

---

## ⚙️ What I Used

* Python
* OpenAI
* OpenRouter
* LiteLLM

---

## 🚀 Project: GPT vs Claude

### 💡 Idea

* GPT: argumentative chatbot 😏
* Claude: polite chatbot 😊
* Both talk to each other in a loop

---

## 🔁 How It Works

* Each model has a role (personality)
* Messages are stored as history
* Models respond to each other step by step

---

## 🧠 Key Learnings

* LLMs can interact with each other, not just users
* Abstraction layers make switching models easier
* Building systems > just calling APIs

---

## 🔥 Next Step

* Add tools
* Add memory
* Build smarter agents 
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
📅 Day 2: Gradio Apps, Streaming & AI Systems
🧠 Overview

In Day 2, I moved from basic API usage to building interactive AI web applications using Gradio.

I learned how to turn LLMs into real products with UI, routing, and real-time responses.

⚙️ What I Used
Python
OpenAI / Claude APIs
OpenRouter
LangChain (basic usage)
Gradio
🚀 Project: AI Multi-Model Web App
💡 Idea

Built a web app where the user can:

Choose between different LLMs (GPT / Claude)
Enter a prompt or URL
Get structured AI output (like a brochure)
🔁 System Flow
User selects model from UI
Request is routed to the chosen LLM
Website content (if URL is provided) is processed
Response is streamed back in real time
🧾 AI Brochure Feature

The system can analyze any website URL and generate a structured AI-powered brochure including:

Company name
Website URL
Summary of content
Key insights
![AI Brochure](images/brochure.png)

⚡ Streaming Feature

Implemented real-time response generation using streaming:

Responses appear gradually (like ChatGPT)
Uses yield to update UI live
Improves user experience significantly
🧠 Key Learnings
How to build AI web apps using Gradio
Difference between API usage and full systems
Streaming responses with LLMs
Building routing logic between multiple models
Turning prompts into real applications
