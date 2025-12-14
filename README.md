AI-HEALTHCARE CHATBOT: IMPLEMENTING AI CHATBOTS IN HEALTHCARE USING META LLAMA MODELS

A web-based application that utilizes advanced Computer Vision LLMs (Llama 3.2 Vision) to analyze medical images and answer user queries in real-time. This project leverages the **FastAPI** framework for the backend and **Groq Cloud API** for high-speed model inference.

 Features

* Medical Image Analysis: Upload images (e.g., skin conditions, X-rays, or diagrams) for AI interpretation.
* Dual-Model Comparison: Simultaneously fetches and displays analysis from two different models for cross-verification:
* `llama-3.2-11b-vision-preview` (Faster, lightweight)
* `llama-3.2-90b-vision-preview` (More detailed, high accuracy).
* Interactive Chat Interface:Users can ask specific questions about the uploaded image.
* Modern UI: Built with Tailwind CSS featuring a dark-mode aesthetic.
* FastAPI Backend: Asynchronous request handling for quick responses.

 Tech Stack

* Backend: Python, FastAPI, Uvicorn
* Frontend: HTML5, JavaScript, Tailwind CSS, Jinja2 Templates
* AI/LLM Provider: Groq API (Llama 3.2 Vision models)
* Image Processing: Pillow (PIL)
* Utilities: Python-dotenv, Requests

 Project Structure

   text
ai_medical_chatbot/
├── app.py                # Main FastAPI application server
├── main.py               # Standalone script for testing CLI/Script usage
├── .env                  # Environment variables (API Keys)
├── templates/
│   └── index.html        # Frontend user interface
├── test1.png             # Test image (Transformer architecture)
├── test2.jpg             # Test image (Skin condition)
└── test3.png             # Test image (Scalp condition)
