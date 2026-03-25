🎧 SonicStudy — AI Audio Flashcards from PDFs

"Status" (https://img.shields.io/badge/status-active-success)
"Frontend" (https://img.shields.io/badge/frontend-React%2018-blue)
"License" (https://img.shields.io/badge/license-MIT-green)
"Made With" (https://img.shields.io/badge/made%20with-JavaScript-yellow)

---

🚀 Overview

SonicStudy is an AI-powered web app that converts textbooks and study materials into interactive audio flashcards.

Upload a PDF → Extract key concepts → Listen with dual voices → Learn faster.

This project focuses on auditory learning enhancement, helping students retain information through multi-sensory engagement.

---

✨ Key Features

- 📄 PDF to Flashcards
  
  - Extracts text using PDF.js
  - Automatically generates term-definition pairs

- 🧠 AI-Powered Extraction
  
  - Claude API (optional) for high-quality NLP
  - Smart fallback heuristic extraction

- 🔊 Dual Voice Audio System
  
  - Term → Voice A
  - Definition → Voice B
  - Powered by Murf AI (or browser TTS fallback)

- 📚 Deck-Based Learning
  
  - Auto-organized flashcard decks
  - Clean, modern UI

- 🔍 Search & Navigation
  
  - Instantly find terms or definitions

- 📊 Progress Tracking
  
  - Audio generation progress indicator

- 🔐 Authentication (Client-side)
  
  - Local login/register system
  - Password hashing (SHA-256)

- ⚙️ API Key Integration
  
  - Murf AI → Voice generation
  - Claude API → NLP extraction

---

🧠 How It Works

flowchart TD
    A[Upload PDF] --> B[Extract Text]
    B --> C[AI / Heuristic Processing]
    C --> D[Generate Flashcards]
    D --> E[Generate Audio]
    E --> F[Play & Learn]

---

🛠️ Tech Stack

Category| Technology
Frontend| React (CDN)
Styling| Custom CSS
PDF Parsing| PDF.js
NLP (Optional)| Claude API
TTS| Murf AI / Web Speech API
Storage| LocalStorage

---

📂 Project Structure

sonicstudy.html   # Complete single-page application

---

⚡ Getting Started

🔹 Run Locally

1. Clone the repository

git clone https://github.com/your-username/sonicstudy.git

2. Open the file in browser

open sonicstudy.html

---

🔹 Deploy Online

Option 1: Netlify

1. Go to Netlify
2. Drag & drop "sonicstudy.html"
3. Your app is live 🚀

Option 2: Vercel

1. Create new project
2. Upload file
3. Deploy

---

🔑 API Setup (Optional but Recommended)

Murf AI (Voice)

- Get key from: https://murf.ai
- Add in Settings → Murf API Key

Claude API (NLP)

- Get key from: https://console.anthropic.com
- Add in Settings → Claude API Key

---

⚠️ Limitations

- ❌ No backend (data stored in browser only)
- ❌ Not suitable for scanned/image PDFs
- ❌ Basic authentication (not production secure)

---

🔮 Future Enhancements

- ✅ Cloud database (Firebase / Supabase)
- ✅ Spaced repetition algorithm (SRS)
- ✅ Mobile app version
- ✅ Multi-language support
- ✅ Collaborative decks

---

💼 Portfolio Description (Use This)

«Built an AI-powered web application that converts PDFs into audio flashcards using NLP and text-to-speech technologies. Integrated Murf AI for dual-voice output and implemented client-side authentication, PDF parsing, and intelligent content extraction to enhance auditory learning experiences.»

---

📸 Demo Preview

Add screenshots here

---

📜 License

This project is licensed under the MIT License.

---

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

⭐ Show Your Support

If you like this project:

- ⭐ Star this repo
- 🍴 Fork it
- 🧠 Use it for learning

---

👨‍💻 Author

R.Harsha Vardhan

---

«“Study smarter, not harder — with sound.”»
