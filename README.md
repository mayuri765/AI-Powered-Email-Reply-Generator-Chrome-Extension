# AI-Powered Email Reply Generator Chrome Extension

An AI-powered Chrome extension that integrates directly with Gmail to generate intelligent email replies automatically. This project helps users save time by providing instant AI-generated responses inside the Gmail compose window.

## 🚀 Features

* Generate AI-based email replies instantly
* Gmail compose window integration
* Custom “AI Reply” button injection
* Dynamic Gmail UI detection using MutationObserver
* React frontend for user interaction
* Spring Boot backend for API handling
* Chrome Extension built using Manifest V3
* Fast and user-friendly interface

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Backend

* Spring Boot
* Java
* REST APIs

### Chrome Extension

* Manifest V3
* DOM Manipulation
* Gmail Integration

---

## 📂 Project Structure

```bash
AI-Powered-Email-Reply-Generator-Chrome-Extension/
│
├── email-writer-ext      # Chrome Extension
├── email-writer-react    # React Frontend
├── email-writer-sb       # Spring Boot Backend
```

---

## ⚙️ How It Works

1. User opens Gmail compose window
2. Extension detects compose section dynamically
3. “AI Reply” button is injected into Gmail toolbar
4. Email content is sent to backend API
5. AI generates smart email reply
6. Generated response is displayed instantly

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/AI-Powered-Email-Reply-Generator-Chrome-Extension.git
```

---

### Frontend Setup

```bash
cd email-writer-react
npm install
npm run dev
```

---

### Backend Setup

```bash
cd email-writer-sb
./mvnw spring-boot:run
```

---

### Load Chrome Extension

1. Open Chrome
2. Go to `chrome://extensions/`
3. Enable Developer Mode
4. Click “Load Unpacked”
5. Select `email-writer-ext` folder

---

## 📌 Future Enhancements

* Multiple email reply tones
* Multi-language support
* Voice-to-email reply generation
* Email summarization
* AI personalization
* Chrome Web Store deployment

---

## 💡 Learning Outcomes

* Chrome Extension Development
* React Frontend Development
* Spring Boot API Development
* Gmail DOM Manipulation
* Full Stack Project Integration
* AI API Integration

---



