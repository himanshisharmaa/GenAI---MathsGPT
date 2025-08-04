# Text to Math Problem Solver & Data Search Assistant

This is a Streamlit-based web application that uses **Google Gemma 2 (via Groq)** and **LangChain** to create an intelligent assistant capable of:
- Solving math word problems with step-by-step logic
- Answering logic and reasoning questions
- Fetching real-time information from Wikipedia

---

## Features

- **Math Solver**: Breaks down mathematical expressions or word problems step-by-step using `LLMMathChain`.
- **Reasoning Tool**: Uses a custom prompt chain to solve logical and reasoning-based questions.
- **Wikipedia Tool**: Answers general queries using real-time Wikipedia lookups.
- **LangChain Agents**: Combines all tools into a single Zero-Shot React agent for flexible problem solving.
- **Groq API**: Fast inference from Gemma 2 model via Groq's high-speed LPU backend.

---

## Tech Stack

- [Streamlit](https://streamlit.io/) – UI Framework
- [LangChain](https://www.langchain.com/) – Tool and agent orchestration
- [Google Gemma 2](https://ai.google.dev/gemma) – Language model (via Groq)
- [Groq API](https://groq.com/) – High-performance inference
- [WikipediaAPIWrapper](https://python.langchain.com/docs/integrations/tools/wikipedia) – Knowledge retrieval

