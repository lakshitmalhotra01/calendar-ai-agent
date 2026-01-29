# Calendar AI Agent

This project is an AI-powered Calendar Assistant built using n8n.

## Features
- Accepts natural language input (e.g. "Block my calendar tomorrow at 2 PM")
- Extracts structured date & time using AI
- Automatically creates Google Calendar events
- Handles timezone correctly (RFC3339)

## Tech Stack
- n8n
- Groq LLM
- Google Calendar API

## Workflow
1. Chat trigger receives message
2. AI Agent extracts event details
3. Google Calendar event is created

## Example
Input:
"Block my calendar tomorrow at 2 PM for a meeting"

Output:
- Event created in Google Calendar with correct time & timezone
