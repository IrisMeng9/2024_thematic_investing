# Thematic Investing with NLP & LLMs — Acadia Research Project

This repository contains the **semantic signal extraction** and **LLM-powered summarization** components I developed as part of a team-based thematic investing research project at Acadia during Summer 2024.

The project aimed to identify, quantify, and visualize companies' exposure to AI-related themes through textual data, and deliver structured investment insights via automated research tooling.

---

## 🔍 Project Overview

The full project was a team collaboration and included the following components:

| Module | Description | Contributor |
|--------|-------------|-------------|
| 🧠 NLP Signal Extraction | Classification of company documents into AI/ESG sub-sectors using BART + ElasticSearch | (Me) |
| 📊 Portfolio Construction | Thematic portfolio optimization via Sequential Least Squares (Sharpe ratio optimization) | [Teammate] |
| 🤖 GPT Chatbot Delivery | Chatbot interface for real-time investor Q&A using GPT APIs | [Teammate] |

This repo includes **only the components I personally implemented and maintained.**

---

## 📌 My Contributions (This Repo)

### 1. Semantic Signal Extraction
- Indexed company descriptions and transcripts using **ElasticSearch**
- Applied a **BART-based classifier** to assign firms into sub-sectors such as `AI-Chips`, `AI-Cloud`, etc.
- Generated a sector exposure matrix for thematic research

### 2. LLM-Powered Summarization (Earnings Transcripts)
- Used **prompt engineering with the Autogen framework** to guide LLMs (e.g., GPT) in generating structured summaries:
  - Sentiment (Bullish/Bearish)
  - Growth expectations
  - Risks and product roadmap
- Summaries were designed to support automated sector report generation

---

## 🛠️ Technologies Used

- Python, Hugging Face Transformers, BART
- ElasticSearch for full-text indexing
- OpenAI API + Autogen for multi-agent prompt workflows
- Pandas, NumPy for preprocessing

---

## 🤝 Acknowledgments

This was a team project conducted under Acadia’s summer industry research program.  
Special thanks to my collaborators for their work on the portfolio and chatbot modules, respectively.

