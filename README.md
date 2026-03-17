# Multilingual Answer Evaluation System

An AI-powered **ML/DL project** that automatically evaluates user answers against reference answers **across languages (English & Hindi)** using semantic similarity. The system generates questions from a given context, accepts user responses, compares them with ground-truth answers, and ranks users based on answer similarity.
<img width="584" height="150" alt="Screenshot 2026-02-16 001705" src="https://github.com/user-attachments/assets/5755011e-665c-43af-8d8a-b34ec76a8133" />

---

## 🚀 Project Overview

This project focuses on **automated answer evaluation** for descriptive answers, even when the **question, reference answer, and user answer are in different languages**.

### Key Capabilities

* 📄 Accepts **input context in English**
* ❓ Automatically **generates multiple questions** from the context
* ✍️ Users answer in **English or Hindi**
* 🌐 Uses **cross-lingual embeddings** to compare answers
* 📊 Scores and **ranks users** based on semantic similarity
* 🧠 Supports **ML + Deep Learning** models

---

## 🧠 System Architecture

```
Input Context (English)
        │
        ▼
Question Generation Model
        │
        ▼
Reference Answers (EN / HI)
        │
        ▼
User Answers (EN / HI)
        │
        ▼
Multilingual Encoder (DL)
        │
        ▼
Embedding Similarity (Cosine)
        │
        ▼
Scores + Ranking
```

---

## 🛠️ Tech Stack

### Machine Learning / AI

* Sentence Transformers (Multilingual)
* BERT / mBERT / XLM-R
* Cosine Similarity
* Question Generation Models (T5 / BART)

### Backend

* Python
* FastAPI
* Uvicorn

### Frontend

* React / Next.js
* Tailwind CSS

### Deployment

* Vercel (Frontend)
* Local / Cloud (Backend)

---

## 📂 Project Structure

```
ml-answer-evaluation/
│
├── backend/
│   ├── main.py
│   ├── models/
│   ├── services/
│   └── utils/
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── notebooks/
│   └── experiments.ipynb
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/projectbyghsx-png/ml-answer-evaluation.git
cd ml-answer-evaluation
```

### 2️⃣ Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Example Use Case

1. Teacher uploads a **paragraph (English)**
2. System generates **3 conceptual questions**
3. Students answer in **English or Hindi**
4. AI evaluates answers semantically
5. Students receive **scores & rank**

---
## Architectural Diagrams

<img width="1762" height="797" alt="Architecture" src="https://github.com/user-attachments/assets/a7f8fd73-e18c-451c-befe-e79850fdd803" />
<img width="1724" height="722" alt="DFD" src="https://github.com/user-attachments/assets/128aa76a-7347-410a-bda4-0dbb311e65a9" />
<img width="1225" height="665" alt="Screenshot 2026-01-30 133922" src="https://github.com/user-attachments/assets/c9d11325-d387-4c6c-8557-215e0d49d8a1" />
<img width="1503" height="814" alt="Screenshot 2026-02-01 194503" src="https://github.com/user-attachments/assets/22d4a857-4491-46c9-82fb-6ea453fc92ad" />
<img width="1585" height="517" alt="Screenshot 2026-02-01 215822" src="https://github.com/user-attachments/assets/605d8051-35a7-42f2-9d6d-f8c66d2e0436" />

## 📈 Evaluation Method

* Text → Multilingual Embeddings
* Similarity → Cosine Similarity
* Score Normalization → 0–100
* Ranking → Highest similarity first

---

## 🔮 Future Enhancements

* 📝 Handwritten answer evaluation (OCR)
* 🌍 More language support
* 📊 Teacher analytics dashboard
* 🤖 LLM-based feedback generation
* 🎯 Partial credit & keyword weighting

---

## 👥 Contributors

* ** Hrishikesh Rajput ** (Owner & System Designer, OCR pipline)
* ** Guneet Chawla  ** 
* ** Saikat Biswas ** 

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you like this project, **give it a star ⭐ on GitHub** and feel free to contribute!

---

**Built with ❤️ for AI-driven education & evaluation**
