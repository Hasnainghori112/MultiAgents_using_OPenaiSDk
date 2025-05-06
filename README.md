# 🎥 Multi-Agent Content Generator using OpenAI SDK + Gemini (via LiteLLM)

This project is a smart, multi-agent system built with the **OpenAI Agent SDK** and powered by **Gemini models via [LiteLLM](https://github.com/BerriAI/litellm)**. It helps users brainstorm creative **video ideas** and generate short, compelling **scripts**.

---

## 🚀 Features

- 🤖 **Idea Generator Agent** – Suggests creative video ideas based on any topic.
- ✍️ **Content Writer Agent** – Writes a 100-word script based on the selected idea.
- 🧠 **Manager Agent** – Routes user input to the correct agent (idea generation or content writing).

---

## 🔧 Powered by LiteLLM 🔥

Instead of calling Gemini directly, this project uses **LiteLLM**, a powerful open-source wrapper that:
- Provides a unified interface for different LLMs (Gemini, Claude, OpenAI, etc.)
- Makes switching models easy with one line of code
- Supports usage in OpenAI Agent SDK out of the box

## 🧩 Technologies Used

- Python 🐍
- [OpenAI Agent SDK](https://github.com/openai/openagents)
- Google Gemini (via LiteLLM)
- asyncio & nest_asyncio for async flow
