# Real-Time Teacher (Gemini 3 Hackathon MVP)

Web kamera + mikrofon bilan qisqa audio yozib yuborasiz.
Backend Gemini 3 Flash orqali:
- mavzuni aniqlaydi
- sinfga mos tushuntirish beradi
- quick quiz + uyga vazifa chiqaradi (JSON)

## O‘rnatish (Windows)
```bat
cd backend
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
copy .env.example .env
notepad .env
uvicorn main:app --reload --port 8000
```

Brauzer:
http://localhost:8000
