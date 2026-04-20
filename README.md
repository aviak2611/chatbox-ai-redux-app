# 🤖 Chatbox AI Application

## 🚀 Overview

This is a full-stack Chatbox application that allows users to interact with AI in real-time.
Users can send messages and receive AI-generated responses instantly through API integration.

---

## 🛠️ Tech Stack

* **Frontend:** React, Redux Toolkit
* **Backend:** Node.js, Express
* **API:** OpenRouter AI API

---

## ✨ Features

* 💬 Real-time AI chat interaction
* 🧠 Global state management using Redux Toolkit
* ⚡ Async API handling using createAsyncThunk
* ⏳ Loading indicator for better user experience
* ❌ Error handling with retry functionality
* 📱 Responsive UI (mobile + desktop)
* 🔐 Secure API integration via backend

---

## 🔄 Project Flow

1. User enters message
2. Frontend sends request to backend
3. Backend calls AI API
4. AI response is received
5. Redux updates state
6. UI displays the response

---

## 📸 Screenshots

(Add your screenshots here)

---

## ▶️ Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/aviak2611/chatbox-ai-redux-app.git
cd chatbox-ai-redux-app
```

---

### 2️⃣ Install Frontend Dependencies

```bash
npm install
```

---

### 3️⃣ Start Frontend

```bash
npm start
```

---

### 4️⃣ Setup Backend

Open a new terminal:

```bash
cd server
npm install
```

---

### 5️⃣ Create .env File (inside server folder)

```env
OPENROUTER_API_KEY=your_api_key_here
```

---

### 6️⃣ Start Backend

```bash
npm start
```

---

## 🔐 Security

* API keys are stored securely using `.env`
* `.env` file is excluded using `.gitignore`
* Backend acts as a secure middleware

---

## 💡 Key Learnings

* Managed global state using Redux Toolkit
* Handled asynchronous API calls using createAsyncThunk
* Built full-stack communication between frontend and backend
* Implemented proper error handling and loading states
* Learned secure API handling practices

---

## 🚀 Future Improvements

* User authentication (login/signup)
* Store chat history using MongoDB
* Streaming responses (typing effect like ChatGPT)
* UI enhancements with timestamps and chat bubbles

---

## 🙌 Acknowledgment

This project was built as part of a technical assignment to demonstrate full-stack development and state management skills.
