# n8n AI Social Content Automation

An n8n workflow template that automatically converts article links into
LinkedIn and X (Twitter) posts using Google Gemini.

## What this template does
- Monitors Google Sheets for new article links
- Summarizes content using AI
- Generates platform-specific posts
- Auto-publishes to LinkedIn and X

## How to use
1. Import the JSON workflow into n8n
2. Add your own credentials (Google, LinkedIn, X, Gemini)
3. Update the Google Sheet with article links
4. Activate the workflow

## Requirements
- n8n (cloud or self-hosted)
- Google Sheets access
- Google Gemini API
- LinkedIn & X developer access

## Security
- No API keys are hardcoded
- Uses n8n credential manager

## License
MIT
