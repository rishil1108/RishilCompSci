# RishilCompSci
Repository for senior seminar
# 🧠 MindMatch: Virtual Sports Psychologist for Collegiate Tennis Athletes

**MindMatch** is an AI-powered journaling chatbot designed to help collegiate tennis players improve their mental performance and emotional resilience. Built using Python, OpenAI's GPT-4 API, and Gradio, it simulates a virtual sports psychologist by providing feedback, mindfulness techniques, affirmations, and visual mood tracking based on journal reflections.

---

## 📘 Project Overview

MindMatch fills the gap for athletes who often lack access to consistent psychological support. It offers an accessible, stigma-free, and personalized mental coaching experience. After each practice or match, athletes can log a reflection, receive tailored feedback, track their mood trends, and export their full journal history in PDF format.

---

## 🏗️ How It Works

- Users enter reflections in natural language (e.g., “I played well but lost focus in the second set.”)
- Sentiment analysis is performed using **TextBlob**
- GPT-4 generates a personalized and psychologically grounded response
- An affirmation and mindfulness cue are included based on the sentiment
- Data is saved in a CSV file and visualized as a mood trend chart
- PDF reports of past entries are downloadable
- All functionality is delivered through a Gradio web interface hosted in Google Colab

---

## 🔧 Installation

> 💡 MindMatch is designed to run in [Google Colab](https://colab.research.google.com), so no local installation is required. If you wish to run it locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/mindmatch-chatbot.git
cd mindmatch-chatbot

