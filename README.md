# Ai-chatbot
# 🩺 Healthcare Assistant Chatbot

A lightweight web application built with **Streamlit** and **Hugging Face Transformers** that serves as an AI-powered healthcare assistant. The application uses a hybrid model: predefined rule-based logic for safety-critical topics and a generative AI model (`distilgpt2`) for general user queries.

---

## 🚀 Features

- **Interactive UI:** Web interface powered by Streamlit for easy user interaction.
- **Hybrid Intent Handling:**
  - **Rule-Based Guidance:** Provides instant responses for keywords related to `symptom`, `appointment`, and `medication`.
  - **AI Generation:** Falls back on Hugging Face's `distilgpt2` pipeline for open-ended responses.
- **Text Processing Ready:** Integrated with `nltk` for tokenization and text processing setup.

---

## 🛠️ Tech Stack

- **Frontend/UI:** [Streamlit](https://streamlit.io/)
- **AI/ML Framework:** [Hugging Face Transformers](https://huggingface.co/) (`distilgpt2`)
- **NLP Utilities:** [NLTK](https://www.nltk.org/)
- **Language:** Python 3.8+

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/healthcare-assistant-chatbot.git](https://github.com/your-username/healthcare-assistant-chatbot.git)
   cd healthcare-assistant-chatbot
