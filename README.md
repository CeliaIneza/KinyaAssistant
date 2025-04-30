# KinyaAssistant

**Kinyarwanda Voice Assistant** is an offline, AI-powered voice assistant that understands and speaks Kinyarwanda. It integrates speech recognition, natural language understanding, and text-to-speech (TTS), all wrapped in a clean Gradio web interface.

This project is designed with Rwandan users in mind — developers, educators, researchers, and anyone passionate about preserving the Kinyarwanda language through AI.

---

## 🖼️ Demo Screenshot

<img width="1440" alt="image" src="https://github.com/user-attachments/assets/f99c74f7-1673-49fb-8fbc-85526c824cd8" />

---

## ✨ Key Features

- 🗣️ **Speech-to-Text (STT)** using a NeMo Conformer model fine-tuned for Kinyarwanda.
- 🔊 **Text-to-Speech (TTS)** using the powerful KinyaTTS VITS2 engine.
- 💡 **Rule-based Natural Language Processing** to interpret questions and commands.
- 🌐 **User Interface** built with Gradio that supports:
  - Microphone input
  - Audio uploads
  - Automatic audio response playback
- 🧠 Fully offline — perfect for privacy and low-resource environments.

---

## ⚙️ Installation Guide

### 🔍 Requirements

- Python 3.8+
- `pip` (Python package manager)
- (Optional but recommended) A GPU for faster performance

---

### 📥 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/CeliaIneza/KinyaAssistant.git
   cd kinyarwanda_Voice_AI
   ```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download models (automatic on first run):

```bash
ASR: mbazaNLP/Kinyarwanda_nemo_stt_conformer_model
TTS: Pre-trained KinyaTTS model
```

### Usage 🚀

Running the Web Interface

```bash
python interface.py
```

The interface will launch at:

```bash
http://localhost:7860
```
=======
# KinyaAssistant
