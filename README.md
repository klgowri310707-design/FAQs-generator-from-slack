## FAQ Generator from Slack

## Aim
The aim of this project is to automatically identify frequently asked questions from Slack or community conversations, generate clear FAQ answers using AI, and store them in a knowledge base.

## Problem Statement
In Slack communities, users often ask the same questions repeatedly. Manually reading all conversations and creating FAQs takes time. This project automates that process.

Technologies Used
- Slack
- n8n
- Python
- AI / LLM
- Qwen Cloud Chat Model
- JavaScript
- Notion

## Workflow

Slack
↓
Python
↓
AI Agent
↓
Qwen Cloud Chat Model
↓
JavaScript
↓
Notion

## How It Works

1. Slack provides the community conversations.
2. The Slack node collects the messages.
3. Python cleans and processes the messages.
4. The AI Agent analyzes the conversations.
5. The AI identifies repeated or similar questions.
6. The AI generates a standard question and answer.
7. JavaScript formats the generated FAQ.
8. Notion stores the FAQ in the knowledge base.

## Example

### Slack Messages
- How can I reset my password?
- I forgot my password. How can I change it?
- Where can I reset my password?

### Generated FAQ

Question:How can I reset my password?

Answer: Follow the organization's password reset procedure.

## Benefits
- Reduces repeated questions
- Saves time
- Automates FAQ creation
- Organizes information
- Provides a reusable knowledge base

## Future Improvements
- Detect duplicate FAQs automatically
- Add more AI models
- Support multiple Slack channels
- Add automatic FAQ updates
- Improve search in the knowledge base

## Project Type
AI-powered automation / Agentic AI project
