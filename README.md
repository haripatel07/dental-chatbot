
# Dental Chatbot API

A lightweight **AI-powered dental chatbot API** built using **FastAPI** and **Sentence Transformers**.  
This API can answer common dental health questions by matching user queries to a pre-defined FAQ knowledge base.

---

## Features
- RESTful API built with **FastAPI**
- Dental FAQ knowledge base with semantic search
- **SentenceTransformer** (`all-MiniLM-L6-v2`) for natural language understanding
- CORS enabled for frontend/mobile app integration
- Deployed on **Railway** for easy access

---

## 🛠️ Tech Stack
- **Backend**: FastAPI (Python)
- **NLP Model**: Sentence Transformers (`all-MiniLM-L6-v2`)
- **Deployment**: Railway
- **Tools**: Uvicorn, Pydantic, CORS Middleware

---

## Project Structure
```
├── app.py              # Main FastAPI application
├── requirements.txt    # Dependencies
├── Procfile            # Deployment configuration
├── pip.conf            # Pip configuration
├── __init__.py
├── .gitignore
├── LICENSE
└── README.md
```

---

## Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/haripatel07/dental-chatbot.git
cd dental-chatbot
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the API Locally
```bash
uvicorn app:app --reload
```
Server will start at: `http://127.0.0.1:8000`

---

## 📬 API Endpoints

### **Chatbot Endpoint**
`POST /chatbot`

#### Request (JSON)
```json
{
  "message": "What causes cavities?"
}
```

#### Response (JSON)
```json
{
  "reply": "Cavities are caused by bacteria producing acids that erode the tooth enamel."
}
```

---

## API Testing with Postman

---
## Deployment
This project is deployed on **Railway**.  
👉 [Live API Link](#) *(add your Railway link here)*

---

## License
This project is licensed under the MIT License.

---

## 👨Author
Developed by **Hari Patel**  
GitHub: [@haripatel07](https://github.com/haripatel07)
