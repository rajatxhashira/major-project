KindEye — AI Psychology Chatbot

Technologies: Python · Flask · Meta LLaMA · MySQL

KindEye is an AI-powered psychology chatbot designed to understand users’ emotional context and provide supportive, empathetic responses. The system uses an LLM to interpret message intent, identify emotional patterns, and generate replies that feel natural and personalized.

Features
Emotion-Aware Conversations

Detects user sentiment and conversational tone using a fine-tuned language model.

Adjusts responses based on emotional context for a more human-like interaction.

LLaMA-Based Response Engine

Uses Meta LLaMA for natural language understanding and generation.

Generates context-aware replies that align with the user’s emotional state.

Secure Data Logging

Stores chat logs and user interaction data in MySQL for analysis.

Helps improve future model performance and personalization.

Backend Architecture

Flask-based API handling chat requests and model inference.

Modular structure for easy scaling and model updates.

Project Structure
KindEye/
│── app.py              # Flask backend
│── model/              # LLaMA model and tokenizer
│── utils/              # Preprocessing and helper functions
│── database/           # MySQL connection & schema
│── static/             # Frontend assets (if any)
│── templates/          # HTML templates (if using UI)
│── requirements.txt    # Dependencies

Installation & Setup
# Clone the repository
git clone https://github.com/yourusername/kindeye.git
cd kindeye

# Install dependencies
pip install -r requirements.txt

# Run Flask server
python app.py

Future Improvements
Add voice-based interaction

Deploy on cloud with GPU acceleration

Build a frontend dashboard for emotion analytics


Optimized for low-latency responses.

Designed to handle multiple sessions efficiently.
