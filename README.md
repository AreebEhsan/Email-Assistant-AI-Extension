# Email-Assistant-AI-Extension

An AI-powered Chrome Extension that generates professional email replies directly inside Gmail.  
It integrates a React frontend, a Spring Boot backend API, and a Chrome Extension content script to deliver seamless in-browser automation without requiring Gmail API access.

---

##  Features

- AI-generated email replies based on email thread context
- Direct integration into Gmail's Compose interface
- No Gmail API or OAuth required (uses DOM scraping)
- Spring Boot backend provides OpenAI-based natural language generation
- React frontend (optional) for testing or standalone usage
- Chrome Extension runs locally and injects only on Gmail domains

---


---

## ⚙️ Technologies Used

| Component        | Stack                           |
|------------------|----------------------------------|
| Chrome Extension | JavaScript, DOM APIs             |
| Backend API      | Java 21, Spring Boot 3.5         |
| Frontend UI      | React 18, Vite, Tailwind (opt.)  |
| AI Integration   | OpenAI API (via backend)         |

---




