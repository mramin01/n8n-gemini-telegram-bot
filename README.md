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

💡 Challenges & Learnings
Throughout this project, I encountered and resolved various challenges, including API-related errors and network configuration issues. This project provided me with a deep, practical understanding of how webhooks 
operate, the critical importance of environment variables, and the proper management of secure credentials.


How to Use This Template

After importing the workflow.json file into your n8n environment, you'll need to replace the PLACEHOLDER values with your own real information.

credentials.id: Go to the Credentials section in n8n, create a new Credential for both your Telegram and Google Gemini accounts, and place their respective IDs here. 🔑

webhookId: After activating the workflow, n8n will automatically generate a Webhook address for you. Place this webhook's ID in this section. 🕸️

meta.instanceId: This value is automatically set by n8n and doesn't need to be changed.

By following these steps, your workflow will be correctly connected to your accounts and ready to run. ✨
