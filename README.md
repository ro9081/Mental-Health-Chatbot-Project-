<img width="900" height="434" alt="image" src="https://github.com/user-attachments/assets/481bd724-58d6-4490-8d3a-ff03172e4eb7" />

# Mental-Health-Chatbot-Project-

This is an AI-powered Mental Health Chatbot designed to provide supportive, non-judgmental conversations for users experiencing stress, anxiety, or emotional challenges. A supportive AI-powered chatbot designed to provide mental health resources, coping strategies, and a listening ear for those in need. Overview This chatbot serves as a digital mental health companion, offering:

Evidence-based coping strategies Resource recommendations Stress management techniques Active listening and supportive responses Self-care reminders and guidance

Access the Chatbot You can interact with the Mental Health Chatbot at: https://mental-health-chatbot-qcyl.onrender.com/

Important Disclaimer _ This chatbot is not a replacement for professional mental health services. If you're experiencing a crisis or emergency, please contact a mental health professional, call a crisis helpline, or visit your nearest emergency room. Features

24/7 Availability: Access support whenever you need it Confidential Conversations: Your data is handled with care Evidence-Based Approaches: Resources based on established mental health practices User-Friendly Interface: Simple design for stress-free navigation Personalized Support: Adapts to your specific needs and concerns

## Key Features
💬 Conversational Support: Engages users in supportive mental health discussions using a large language model.

🚨 Crisis Detection System: Identifies high-risk or crisis keywords and responds with pre-defined safety measures.

🧩 Template-Based Responses: Uses customizable JSON templates for structured replies and safety guidance.

🔐 Privacy-Friendly Design: No sensitive user data is stored; responses are generated in real-time.

🖥️ Responsive UI: A clean, mobile-friendly frontend without third-party frameworks.

🌐 Hosted on Render: Easily accessible via a public web link.

## 🛠️ Tech Stack
Python + Flask (Backend)

HTML, CSS, JavaScript (Frontend)

Gemini 1.5 Pro API (LLM)

Render (Deployment)

## Usage Guidelines

Share your thoughts, feelings, or concerns in the chat window Be specific about what you're experiencing for more tailored support Ask for specific resources or techniques if you have preferences Remember that the chatbot works best for non-emergency support

Feedback Your feedback helps improve this service. Please share your experience through the feedback form available in the chatbot interface. Privacy and Data Protection All conversations are confidential. For more information, please review our privacy policy in the application.

<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/ef4f8cf5-acd0-48bd-bb4f-ac2f709a0dff" />

## 🧠 Mental Health Chatbot – System Architecture

## 1. User Interface (Frontend)
   
Technology: HTML, CSS, JavaScript (no external UI frameworks if required)

Features:

Chat window for user interaction

Emojis and friendly UI for mental wellness

Input box and send button

Alert system (e.g., for crisis detection)

Responsive design (mobile + desktop)

## 2. Backend (Flask Application)
Technology: Python + Flask

Routes:

/ → Serves frontend UI

/chat → Handles user input, sends to Gemini, returns response

/crisis-check → Crisis phrase checker (optional route)

Security/Safety Logic:

Filter and flag unsafe or crisis-related messages

Auto-responder with emergency contacts if crisis detected

## 3. Google Gemini (LLM Integration)
Model: Gemini 1.5 Pro or Gemini via API (can be replaced with OpenAI or other LLM)

Functionality:

Processes user messages

Generates empathetic, supportive responses

Follows mental health-safe prompt templates

## 4. Crisis Detection Module
Implementation:

Keyword-based or ML-based phrase checking (e.g., “I want to die”)

Triggers:

JSON safety templates

Emergency advice response

Optional:

Sentiment analysis using TextBlob/VADER for tone detection

## 5. Safety Settings & Response Templates
Templates Stored in JSON:

Greeting messages

Neutral prompts (e.g., “Tell me how you’re feeling.”)

Crisis messages (e.g., “It sounds like you're going through a really hard time. You're not alone...”)

Emergency resources (helpline links, etc.)

## 6. Deployment
Platform: Render / Replit / PythonAnywhere / Heroku / Hugging Face Spaces

Repository: Hosted on GitHub for version control


