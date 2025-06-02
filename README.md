# AI Email Agent using n8n

This project showcases an AI-powered email automation agent built using **n8n**. It allows users to send emails through a simple chat interface with real-time automation.

## Features
- Chat-driven interface
- Automated email sending
- No-code backend via n8n
- Voice-over demo included

## Demo
[Watch the demo video](assets/demo.mp4)  
*(or upload to YouTube and link here)*

## How It Works
- User sends a message via chat
- n8n reads the message and triggers the email node
- Optionally, voice-over is generated using gTTS or pyttsx3

## Tools Used
- [n8n.io](https://n8n.io)
- Python (for voice-over)
- MoviePy (for video editing)
- Google TTS or pyttsx3

## Setup
1. Import the workflow.json into your n8n instance
2. Configure your email credentials
3. Test via chat trigger or HTTP node

## License
MIT
