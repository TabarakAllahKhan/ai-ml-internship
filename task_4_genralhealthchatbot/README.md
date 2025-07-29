# 🩺 General Health Chatbot

This repository contains the **General Health Chatbot**, an internship project developed for **Developers Hub Corporation**. The chatbot provides health tips for common illnesses and suggests general over-the-counter (OTC) medications. It also includes safety filters to restrict unsafe or inappropriate prompts.

The chatbot is powered by the **TinyLLaMA model** from Hugging Face and was initially developed and tested using **Google Colab**.

---

## 💡 Features

- 💬 **Health Query Support**: Responds to user queries regarding common illnesses like flu, fever, cold, headache, etc.
- 💊 **OTC Medicine Suggestions**: Recommends general-purpose medications for minor health issues.
- 🚫 **Prompt Safety Filter**: Prevents users from entering dangerous, offensive, or medically inappropriate inputs.
- 🤖 **Language Model Integration**: Uses TinyLLaMA from Hugging Face for generating responses.

---

## 🧪 Project Background

This chatbot was developed as part of an internship project for **Developers Hub Corporation**. The goal was to build an intelligent assistant that can:

- Provide basic health information conversationally
- Recommend general medications safely
- Handle user input responsibly through filtering

---

## 🚧 Challenges Faced

During the development process, several technical challenges were encountered:

- ⚙️ **Model Size**: TinyLLaMA, while smaller than many language models, is still resource-intensive. Running it locally was impractical.
- 🐢 **Performance Bottlenecks**: Even when moved to Google Colab with GPU acceleration, the response time for each user prompt was relatively slow due to model loading and processing latency.

---

## 🔮 Future Development

Planned improvements for the chatbot include:

- 🌐 **Streamlit Integration**: Building an interactive frontend using Streamlit for easier user interaction.
- 🚀 **Deployment**: Hosting the chatbot as a live web application.
- 📉 **Model Optimization**: Exploring quantization or fine-tuning to reduce response time and improve efficiency.
- 🛡️ **Advanced Prompt Filtering**: Implementing smarter NLP-based filters for enhanced safety and input control.

---

## 🛠️ Tech Stack

- **Python**
- **Google Colab**
- **Hugging Face Transformers**
- **TinyLLaMA Language Model**
- *(Planned)* Streamlit for frontend deployment


