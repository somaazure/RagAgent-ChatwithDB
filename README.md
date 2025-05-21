# RagAgent-ChatwithDB
RagAgent-ChatwithDB

# 🤖 Tesla SQL Agent — GPT-Powered RAG for Vehicle Data

This script builds an intelligent agent that allows you to chat with a Tesla vehicle database using natural language. Powered by OpenAI's `gpt-4o-mini` and LangChain's SQL agent toolkit, it converts your questions into accurate SQL queries with domain-specific reasoning.

## 🚘 Features (by Model Style):

- 🚗 **Model S** — Ask about average prices, specs, and battery ranges
- 🚙 **Model X** — Compare features and performance with other models
- 🚕 **Model 3** — Analyze sales by region, pricing trends, and variants
- 🚐 **Model Y** — Get detailed insights into charging times and capacities
- 🛻 **Cybertruck (Future)** — Identify gaps or missing data when unavailable

## ⚙️ Key Highlights

- 💬 Uses GPT to translate user queries into SQL and return formatted answers
- 🔍 Custom system prompt ensures detailed, context-aware Tesla answers
- 🔒 Read-only SQL agent — safe from insert/update/delete actions
- 📊 Supports trend analysis, comparisons, and region-based insights
- 🎛️ Works via CLI — just enter a question and get intelligent results
- 🔑 Requires only an OpenAI API key and a valid SQLite database file

## 🚀 Getting Started

1. Set your `OPENAI_API_KEY`
2. Update `DB_PATH` in the script
3. Run the script and start asking Tesla-related questions like:
   - *"What’s the average range of Model Y?"*
   - *"Which model has the highest sales in 2022?"*

> ⚡ Tip: The agent will gracefully guide you if your query is unclear or the data is incomplete.


![image](https://github.com/user-attachments/assets/7dc18a4f-442f-459b-9971-08d33ce123c1)
