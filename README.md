## Groq Chat API + UI

This project is a simple full-stack AI application.

It includes:
- Flask backend API deployed on Render
- Groq LLM integration for AI responses
- Basic frontend (HTML + JavaScript) chat UI

---

## Backend

The backend is built using Flask and exposes two endpoints:

- `/` → Health check  
- `/chat` → Accepts POST requests and returns AI responses  

Example request:

POST /chat  
{
  "message": "Hello"
}

---

## Live API

Backend URL:  
https://flask-groq.onrender.com

Chat Endpoint:  
https://flask-groq.onrender.com/chat

---

## Frontend

A simple UI (`index.html`) is included.

It:
- Takes user input
- Sends request to `/chat`
- Displays AI response

To run locally:
- Open `index.html` in browser
- Or use VS Code Live Server

---

## Tech Stack

- Python (Flask)
- Groq API (LLM)
- HTML + JavaScript (fetch API)
- Render (deployment)

---

## Notes

- `/chat` only supports POST (not accessible directly via browser)
- API is public (no authentication added yet)
- Free Render tier may have cold start delays
