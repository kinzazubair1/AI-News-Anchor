# 📰 AI-Powered News Broadcast Project

This project automates the process of scraping the latest news headlines, generating a professional broadcast script, and producing voice-based news audio using AI technologies.

---

## 📌 Features

- 🔍 **News Scraping**: Collects top headlines from:
  - BBC News
  - Al Jazeera
  - Dawn News

- 🧹 **Headline Cleaning**: Removes duplicates and short/incomplete headlines.

- 📝 **Script Generator**: Dynamically creates a readable, broadcast-friendly news script.

- 🗣️ **Text-to-Speech (TTS)**:
  - Supports both **Google Cloud TTS** and **Eleven Labs**.
  - Generates clear, emotionally appropriate narration for the broadcast.

- 🧑‍💻 **Web-Ready Output**:
  - Designed for integration into a **Single Page Web Application**.
  - Intended for future use with a **3D avatar** for lip-sync and facial expression rendering.

---

## 🚀 How to Use

1. Open the Colab Notebook:  
   [Run on Google Colab](https://colab.research.google.com/drive/1k7ELtthcIkEN4s4xCvTWgI1GczKdG1aI)

2. Follow the cells step-by-step:
   - Scrape news from the web
   - Clean and process headlines
   - Generate the broadcast script
   - Convert script to speech using your preferred TTS engine

3. Download the generated MP3 to use in your web app.

---

## 🔗 Dependencies

- `requests`
- `beautifulsoup4`
- `google-cloud-texttospeech`
- Access to [Google Cloud Console](https://console.cloud.google.com/) for API credentials
- Eleven Labs API Key (if using Eleven Labs TTS)

---

## 🛠️ Next Steps

This repo is part of a collaborative project. The next stages include:
- Avatar creation with facial animation and lip-sync
- Integration into a full web application
- Automatic playback of news on page load

---

## 👨‍💻 Contributors
-taiba shafique
-kinza zubair
-aymen shahbaz

## 📄 License

This project is for educational purposes. Attribution required if reused or modified.

