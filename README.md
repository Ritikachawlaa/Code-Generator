# 🤖 CodeCraft – AI-Based Code Generation Platform

**CodeCraft** is an AI-powered platform that generates executable code based on natural language prompts. It uses the **Code LLaMA 7b model** and provides a user-friendly interface via **Streamlit**.

---

## 🚀 Features

- Natural Language → Code (Python, Java, C, C++)
- Built-in UI to control:
  - Max code length
  - Creativity (temperature)
- Real-time generation using Groq API / HuggingFace models
- Download generated code
- Optimized for accuracy, speed, and readability

---

## 🧠 Technologies Used

- Streamlit
- Hugging Face Transformers
- CodeLLaMA-7b-Instruct
- Torch + FP16 Precision

---

## 📦 Installation

---bash

git clone https://github.com/ritika-code/CodeCraft-AI-Code-Generator.git
cd CodeCraft-AI-Code-Generator
pip install -r requirements.txt
streamlit run app.py
