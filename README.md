# whatsapp-ai-agent
AI-powered WhatsApp Assistant built with n8n, OpenAI, and WhatsApp Cloud API. Supports text, voice, and images with multimodal responses, memory, and tools like web search &amp; knowledge base.
WhatsApp AI Assistant 🤖💬

An AI-powered WhatsApp Assistant built with n8n
.
This project integrates OpenAI, WhatsApp Cloud API, and Pinecone to create a multimodal conversational bot called Sam, capable of handling:

🎤 Voice messages → Transcribed & answered in text or voice

🖼️ Images → Analyzed and described with AI

💬 Text messages → Smart AI responses with context

🧠 Memory → 20-message context per user

🔎 Tools → Web search, calculator, knowledge base

✨ Features

✅ Supports Text, Image, and Audio inputs

✅ Replies in Text or Audio (depending on how the user interacts)

✅ Uses OpenAI GPT-4o-mini for conversations

✅ Vision AI to analyze and describe images

✅ Whisper (ASR) to transcribe voice messages

✅ Text-to-Speech to reply with natural voice

✅ Pinecone Knowledge Base for custom context

✅ Web Search + Calculator tools

🛠️ Tech Stack

n8n
 – Workflow automation

WhatsApp Cloud API
 – Messaging integration

OpenAI GPT
 – AI language model

OpenAI Whisper
 – Audio transcription

OpenAI TTS
 – Text-to-speech

Pinecone
 – Vector database for knowledge base

SerpAPI
 – Web search

🚀 Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/whatsapp-ai-assistant.git
cd whatsapp-ai-assistant

2. Import Workflow into n8n

Open n8n

Import the workflow.json file

3. Configure Credentials

You’ll need to set up the following credentials inside n8n:

WhatsApp Cloud API

OpenAI API

SerpAPI (for web search)

Pinecone API

4. Deploy WhatsApp Webhook

Connect your WhatsApp Business Cloud API to n8n

Set webhook URL in Meta Developer Dashboard

5. Start n8n
n8n start

📌 Usage

Send a text, voice note, or image to your WhatsApp number.

The AI assistant (Sam) will analyze and respond.

Text → gets a text reply

Voice → gets a voice reply

Image → gets a description + contextual answer

📷 Demo (Optional)

Add a screenshot or GIF here once you test it.

🗺️ Roadmap

 Add support for document files (PDF, DOCX)

 Multi-language support 🌍

 Deploy as Docker container

🤝 Contributing Thanks

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

📜 License

MIT License – free to use and modify.
