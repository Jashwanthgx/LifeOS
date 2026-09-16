# 🧠 LifeOS: Context-Aware Phone-First Adaptive Assistant

LifeOS is an adaptive, AI-powered personal productivity engine designed to turn chaotic daily schedules into dynamic, manageable plans using native phone hardware capabilities (Camera, Voice, Sensors) and local on-device AI models.

## 📱 Key Phone-First Capabilities
* **📷 Vision & OCR Scanning:** Point phone camera at handwritten assignments, exam schedules, or task lists.
* **🎙️ Voice Capture:** Hands-free context updates while on the move.
* **🤖 Adaptive Re-planning:** Local and hybrid LLM execution via FastAPI backend to re-balance daily tasks based on real-time energy levels and location.

## 🏗️ Architecture & Stack
* **Frontend:** React Native (Expo)
* **Backend:** FastAPI (Python)
* **Local AI:** Ollama / Llama-3 / Vision Models
* **Database / Vector Search:** PostgreSQL & Qdrant
