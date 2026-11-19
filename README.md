# AI Chat Application — Module 03

A lightweight AI Chat web application built for **Module 03: LLM APIs & Application Development** during my Generative AI internship at **Codomax Digital Solutions**.

## Features Implemented
* **LLM API Integration & Demo Mode:** Connects to the Gemini API via REST with client-side key input (never hardcoded in source code) plus an offline fallback mode.
* **Conversation & Chat History:** Tracks multi-turn user and assistant messages and trims context to the latest turns for token efficiency.
* **Custom System Instructions & Parameters:** Allows setting custom system prompts and configures `temperature` and `maxOutputTokens`.
* **Error Handling & Clean UI:** Handles invalid keys or network errors gracefully with a responsive chat interface.
