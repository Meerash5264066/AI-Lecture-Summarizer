# 🎓 AI Lecture Summarizer with Q&A System

## 🚀 Overview

The **AI Lecture Summarizer with Q&A System** is a deep learning-based application that converts long audio/video lectures into structured, multilingual learning content.
It uses speech recognition, natural language processing, and retrieval-based AI to generate summaries, translations, and intelligent answers.

---

## 🔥 Key Features

* 🎥 **Supports long lectures (1–1.5 hours)**
* ⚡ **Fast transcription using Faster-Whisper**
* 🌐 **Automatic language detection**
* 🧹 **Text refinement into meaningful English**
* 📖 **Lecture summarization using transformer models**
* 🌍 **Multi-language translation (8 languages)**
* ❓ **Hybrid Q&A system (RAG + AI fallback)**
* 💻 **Code generation for programming topics**
* 📂 **Downloadable outputs (transcript & notes)**

---

## 🧠 System Architecture

### 🔹 Input Layer

* Audio / Video Upload

### 🔹 Processing Layer

* Audio Extraction (FFmpeg)
* Chunking (5–10 minutes)
* Speech-to-Text (Faster-Whisper)

### 🔹 Intelligence Layer

* Language Detection
* Text Cleaning
* Topic Segmentation
* Summarization (Transformer Models)
* Q&A System (FAISS + Embeddings)

### 🔹 Output Layer

* Transcript
* Summary
* Translated Summary
* Q&A Responses

---

## ⚙️ Technologies Used

### 🧠 Models

* **Faster-Whisper** → Speech Recognition
* **DistilBART / BART** → Summarization
* **Sentence Transformers** → Embeddings
* **FAISS** → Similarity Search (RAG)

### 📚 Libraries

* `transformers`
* `faster-whisper`
* `sentence-transformers`
* `faiss-cpu`
* `deep-translator`
* `langdetect`
* `nltk`
* `pydub`
* `gradio`

---

## 🧪 Workflow

```
Video/Audio Input
        ↓
Audio Extraction
        ↓
Chunking
        ↓
Transcription
        ↓
Text Cleaning
        ↓
Summarization
        ↓
Translation
        ↓
Q&A System
        ↓
Final Output
```

---

## ▶️ How to Run (Google Colab)

1. Open the notebook in Google Colab
2. Run all cells
3. Upload audio/video file
4. Click **Start Processing**
5. View:

   * Transcript
   * Summary
   * Translations
   * Q&A

---

## 📂 Output

* 📜 Full Transcript
* 📖 Summary
* 🌍 Translated Content
* ❓ Question Answers

---

## 🔐 Security Note

⚠️ API keys are **not stored in the code**
Use runtime input:

```python
from getpass import getpass
API_KEY = getpass("Enter API key: ")
```

---

## 🎯 Applications

* 🎓 Students (revision & notes)
* 📚 Online learning platforms
* 🧑‍🏫 Educators
* 🌍 Multi-language learning

---

## ⚠️ Limitations

* Accuracy depends on audio quality
* Long videos require more processing time
* Translation may not be perfect for all languages

---

## 🚀 Future Improvements

* Real-time lecture processing
* Better topic segmentation
* Improved multilingual accuracy
* Web deployment (Streamlit / Flask)

---

## 🧑‍💻 Author

**Meerash N**
AI & Deep Learning Project

---

## ⭐ Conclusion

This system transforms raw lecture content into structured, accessible, and multilingual knowledge using AI — making learning faster, easier, and more interactive.

---
