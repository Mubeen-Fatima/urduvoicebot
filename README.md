# 🤖 Urdu AI Chatbot with Voice – Built using Streamlit & Gemini

An intelligent conversational AI chatbot for the **Urdu language**, enabling natural, human-like voice interactions using **Gemini LLM** and **Streamlit**.

🔗 **Live App:** [urduvoicebot.streamlit.app](https://urduvoicebot.streamlit.app/)
🎥 **Demo Video:** [Watch on YouTube](https://youtu.be/w2ezpusfzfs)

---

## 🎯 Features

* 🎙️ **Voice-to-Text in Urdu** using Google Speech Recognition API
* 💬 **Natural Language Understanding** via Gemini LLM
* 🔊 **Text-to-Speech (TTS) in Urdu** using Google Text-to-Speech API
* 🌐 **Streamlit Interface** for interactive use
* 🧠 *Optional fine-tuning of LLM for better Urdu understanding*

---

## 🛠️ How It Works

1. **Speech Recognition**
   → Convert user's Urdu voice input into text using Google Speech API.

2. **Language Processing with Gemini**
   → Feed the text to the Gemini LLM for generating a relevant response.

3. **Text-to-Speech Conversion**
   → Convert Gemini's Urdu text response into audio using Google TTS API.

4. **Streamlit App UI**
   → Everything runs in an interactive Streamlit web interface.

---

## 🚀 Getting Started

### 📦 Prerequisites

Ensure you have the following installed:

* Python 3.8 or above
* `pip` (Python package manager)
* API key for Gemini (from Google AI Studio)

---

### 🧩 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Mubeen-Fatima/urdu-voice-chatbot.git
   cd urdu-voice-chatbot
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Secrets**

   This project uses Streamlit secrets management. Create a `.streamlit/secrets.toml` file:

   ```toml
   [gemini]
   GEMINI_API_KEY = "your_gemini_api_key"
   ```

5. **Run the App**

   ```bash
   streamlit run app.py
   ```

---

## 📁 Project Structure

```bash
urdu-voice-chatbot/
├── voicechatbot.py       # Main Streamlit app
├── requirements.txt      # Python dependencies
└── .streamlit/
    └── secrets.toml      # API key configuration
```

---

## 🙋‍♂️ Developed By

**[Mubeen F.](https://mubeenf.com)**
Feel free to fork, contribute, or reach out for collaboration!

---
