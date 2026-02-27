# AI Email Reply with chrome  extension

AI-powered email reply generator built with **Spring Boot**, **React (Vite)**, and a **browser extension**.
The project helps users generate professional email replies using AI via a web app and extension.

---

## Project Structure

```text
AI-Email-Reply/
├── email-writer-backend/     # Spring Boot backend
├── email-writer-frontend/    # React + Vite frontend
├── extension/                # Browser extension
├── .gitignore
└── README.md
```

---

## Tech Stack

### Backend

* Java
* Spring Boot
* Maven
* REST APIs

### Frontend

* React
* Vite
* JavaScript
* HTML / CSS

### Extension

* Chrome / Edge Extension
* JavaScript

---

## Features

* Generate AI-based email replies
* Choose tone and context
* Web-based UI
* Browser extension for quick replies
* REST-based backend architecture

---

## Prerequisites

* Java 17+
* Maven
* Node.js 16+
* npm
* Chrome / Edge browser

---

## Running the Project

### Backend (Spring Boot)

```bash
cd email-writer-backend
./mvnw spring-boot:run
```

For Windows:

```bash
mvnw spring-boot:run
```

Backend runs at:

```
http://localhost:8080
```

---

### Frontend (Vite + React)

```bash
cd email-writer-frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

### Browser Extension

1. Open Chrome / Edge
2. Go to `chrome://extensions`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select the `extension/` folder

---

## Configuration

Add your AI API key in backend configuration:

```properties
application.properties
OPENAI_API_KEY=your_api_key_here
```

(Adjust based on AI provider used.)

---

## Usage

1. Start backend and frontend
2. Enter email content and tone
3. Generate AI reply
4. Use extension for quick replies in browser

---

## Deployment 

* Backend: Render 
* Frontend: Vercel
* Extension: Chrome Web Store(not done yet)

---

Demo : https://email-reply-frontend-kappa.vercel.app/



