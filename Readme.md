# 🎓 RealTime Teacher — AI Classroom Copilot

**RealTime Teacher** is a real-time AI assistant for teachers that listens, observes, and supports live classroom lessons using **Google Gemini 3**.

It helps teachers explain topics, generate quizzes, adapt lessons, and provide instant feedback while the lesson is happening.

---

## 🚀 What It Does

- 🎙️ Live microphone input (push-to-talk or continuous mode)
- 📷 Camera snapshots for visual classroom context
- 🧠 Real-time AI lesson generation with Gemini 3
- 📝 Automatic summaries, key points, quizzes, and homework
- 🧩 Grade & subject adaptation (e.g. Grade 7 Informatics)
- 🖥️ Packaged as a one-click desktop application for teachers

---

## 🧠 Why It Matters

Teachers manage many cognitive tasks at once: explaining content, observing students, answering questions, and adapting their teaching.

RealTime Teacher becomes a **classroom co-pilot** that works *during* the lesson — not after.

---

## 🛠️ Built With

- **Python**
- **FastAPI**
- **Google Gemini 3 API**
- **HTML / CSS / JavaScript**
- **WebView**
- **PyInstaller**

---

## ⚙️ How It Works

1. Teacher starts the desktop app.
2. Audio and camera data are captured in real time.
3. The backend sends multimodal input to **Gemini 3**.
4. Gemini generates structured lesson output:
   - Explanation
   - Key points
   - Quizzes
   - Homework
   - Teaching tips
5. Results appear instantly in the classroom UI.

---

## 🖥️ Running the App (for demo)

```bash
# inside project folder
python desktop_app.py
