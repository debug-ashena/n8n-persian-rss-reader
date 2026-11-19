# n8n-persian-rss-reader
An open-source agent for reading and translating the state-of-the-art technology news around IT, AI , and CyberSecurity. The news is engaging sysadmins, web hosting technical support teams, and all web-hosting companies.

# Persian RSS News Reader Workflow for n8n

An automated n8n workflow that fetches multiple Persian and tech RSS feeds (like WordPress, Cloudflare, HackerNews), processes and summarizes the content using AI, and publishes/delivers the results smoothly.

## Features
- 🔄 Automated RSS Feed Fetching
- 🤖 AI Content Summarization & Processing
- ⏱️ Smart Rate Limiting & Flow Control (Wait & Filter nodes)
- 🚀 Telegram/Notification integration ready

## Prerequisites
- n8n (Self-hosted via Docker recommended)
- PostgreSQL (or standard n8n database)
- AI Provider API Key (OpenAI / AvalAI / etc.)

## Installation & Setup
1. Download the JSON workflow file from this repository (`rss-workflow.json`).
2. Import the workflow into your n8n dashboard.
3. Configure your credentials:
   - RSS / HTTP Request nodes
   - AI Model Node credentials
   - Telegram Bot Token / Chat ID (or your preferred output node)
4. Adjust the Filter and Wait nodes according to your posting frequency (e.g., 3600 seconds delay).

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
