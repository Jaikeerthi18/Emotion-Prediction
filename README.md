# Emotion-Prediction
Emotion Prediction using BiGRU is a deep learning-based web application that predicts human emotions from text. The project uses a Bidirectional GRU (BiGRU) neural network trained on textual data to classify input sentences into different emotion categories.
# 🧠 Emotion Prediction using BiGRU

A deep learning-based web application that predicts human emotions from text using a **Bidirectional Gated Recurrent Unit (BiGRU)** neural network. The trained model is deployed using **FastAPI** and provides real-time emotion predictions through a simple web interface.

---

## 📌 Project Overview

Emotion Prediction is a Natural Language Processing (NLP) project designed to identify the emotional state expressed in a given text.

The project uses a **BiGRU deep learning model** to understand the context and sequence of words in a sentence. The input text is first processed using a trained tokenizer and converted into numerical sequences. These sequences are then passed to the BiGRU model to predict the corresponding emotion.

The trained model is integrated with a **FastAPI backend**, while a lightweight HTML, CSS, and JavaScript frontend provides an easy-to-use interface.

---

## ✨ Features

- 🧠 BiGRU-based deep learning model
- 💬 Text-based emotion classification
- 🔤 Pre-trained text tokenizer
- ⚡ FastAPI REST API
- 🌐 Interactive web interface
- 🚀 Real-time emotion prediction
- ❤️ Multiple emotion classification
- 🏥 Health-check API endpoint
- 📦 Saved trained model for deployment
- 📓 Jupyter Notebook for model development

---

## 🏗️ Project Architecture

```text
                   User Input
                       │
                       ▼
              ┌─────────────────┐
              │   Web Interface │
              │ HTML/CSS/JS     │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    FastAPI      │
              │    Backend      │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    Tokenizer    │
              │ tokenizer.pkl   │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   BiGRU Model   │
              │ TensorFlow/Keras│
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ Emotion Output  │
              └─────────────────┘
