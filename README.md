# Customer Support Workflow with Groq + LangChain
#### 📌 Overview
This project is a customer support AI assistant built using LangChain and Groq API.
It can categorize customer queries, analyze sentiment, and route them to the appropriate handler (technical, billing, general, or escalation)

#### 🚀 Features

- Categorization of customer queries
- Sentiment analysis (Positive, Negative, Neutral)
- Routing to the correct support workflow
- Handlers for technical, billing, general, and escalation cases
- Groq-powered LLMs for fast inference

#### 🔄 Workflow

- Categorize Query – Determine if the query is about Technical, Billing, or General issues.
- Analyze Sentiment – Check if the tone is Positive, Negative, or Neutral.
- Routing:
   - If Negative sentiment → Escalate
   - If Technical issue → Technical handler
  - If Billing issue → Billing handler
  - Else → General handler
- Response – Provide the correct resolution or escalate for further support.

#### 🛠 Tech Stack
- Python

- LangChain – Orchestration and workflow management

- Groq API – LLM for categorization and sentiment analysis

- LangGraph – State-based workflow (nodes + conditional routing)
