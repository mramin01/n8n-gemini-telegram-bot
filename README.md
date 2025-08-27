🤖 AI-Powered Telegram Assistant with n8n & Gemini
This is an advanced, intelligent Telegram bot built on the n8n automation platform, powered by the potent Google Gemini 2.5 Flash model. This project serves as a portfolio piece to demonstrate proficiency in API integration, workflow design, and working with large language models (LLMs).

✨ Features
Intelligent Responses: Engages in fluent conversations and provides insightful answers to a wide range of questions using the power of Gemini 2.5 Flash.

Rapid Processing: Leverages the Flash model to deliver real-time, low-latency responses, ensuring a smooth user experience.

Scalable Architecture: Built with a simple and extensible architecture that allows for easy addition of new features and capabilities in the future.

🛠️ Tech Stack
n8n: The core platform for designing and executing the automation workflow.

Google Gemini API: The thinking brain of the bot, responsible for understanding and generating responses.

Telegram Bot API: The interface for communication within the Telegram messenger app.

Ngrok: Used to create a secure tunnel for local development and testing.

🚀 Getting Started
Clone this repository or download the workflow.json file.

Import the workflow.json file into your n8n environment.

Create a new Credential for your Telegram Bot.

Create a new Credential for your Google Gemini API and link it to the corresponding node.

Activate the workflow and enjoy your intelligent assistant!


About This Code 📝
To keep your information secure and allow you to share this workflow publicly, I've removed the sensitive information from the JSON file.

Changes Made ✂️
I've taken these values from the original code and replaced them with PLACEHOLDER:

credentials.id: This is a specific identifier that connects to your user account (like Telegram or Google Gemini). Anyone who wants to use this workflow must create their own credential and place it here. 🔑

webhookId: This ID is used to establish a connection with the Webhook in n8n. Every workflow has a unique webhookId that should not be made public. 🕸️

meta.instanceId: This is an internal ID for the n8n instance itself, and it's best to remove it in public sharing. 🆔

With these changes, your workflow becomes a clean and secure template that others can easily import into their own n8n instance and replace the sensitive information. 🛡️

💡 Challenges & Learnings
Throughout this project, I encountered and resolved various challenges, including API-related errors and network configuration issues. This project provided me with a deep, practical understanding of how webhooks operate, the critical importance of environment variables, and the proper management of secure credentials.
