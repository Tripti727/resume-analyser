# Resume Analyser

## 📌 Overview
Resume Analyser ek FastAPI based backend hai jo resumes ko job descriptions ke against analyse karta hai aur feedback provide karta hai:
- Missing skills aur weak points detect karta hai
- ATS compliance check karta hai
- Semantic similarity score calculate karta hai
- Improved resume draft generate karta hai (on explicit request)

---

## 🚀 Features
- Multi-format resume parsing (PDF, DOCX, TXT)
- Gap detection (skills, achievements, sections)
- ATS compliance validator
- Resume scorecard (0–100)
- Privacy protection (mask email, phone, address)
- HuggingFace/Groq models for resume generation (no OpenAI)

---

## ⚙️ Setup

### 1. Clone repository
```bash
git clone https://github.com/yourusername/resume-analyser.git
cd resume-analyser
