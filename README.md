# -LLM-based-Chat-Assistant-Nova-


# Nova - Your Personal Voice Assistant (Python)

**Nova** is a smart desktop voice assistant built using Python. It helps users interact with their system and the internet using natural voice commands. Powered by speech recognition, text-to-speech, and Gemini API integration, Nova performs various tasks like opening websites, adjusting brightness/volume, drafting emails, playing YouTube videos, and responding to AI prompts.

---

## 🔧 Features

- 🎤 **Voice-Activated Interface**  
  Control the assistant using voice with Google Speech Recognition.

- 💬 **Text-to-Speech Responses**  
  Uses SAPI.SpVoice (Windows only) to respond audibly.

- 🌞 **Control Brightness**  
  Increase/decrease screen brightness by 10%.

- 🔊 **Control Volume**  
  Increase/decrease system volume.

- 🌐 **Open Websites and Applications**  
  Open popular websites or local applications via voice command.

- 📧 **Send Emails**  
  Draft email using your voice (opens default mail client with content prefilled).

- 🎥 **Play YouTube Videos**  
  Search and play YouTube videos using `pytube`.

- 🤖 **Ask AI (Gemini API)**  
  Send prompts to Google's Gemini API and get responses saved to local files.

---

## 📦 Requirements

Install dependencies via `pip`:

```bash
pip install SpeechRecognition pywin32 screen_brightness_control pycaw requests pytube3
