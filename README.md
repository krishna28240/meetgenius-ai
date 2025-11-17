# MeetGenius AI
MeetGenius AI is an intelligent meeting summarizer that converts Google Meet transcripts into actionable summaries, decisions, and task lists — and syncs them with Google Calendar, Gmail, and Google Sheets.

## Project Structure
/frontend → React UI (login, transcript upload, results UI)
/backend → Node.js backend (API orchestrator, OAuth, Google API actions)
/llm-service → Gemini or Gemma/Ollama LLM service (Cloud Run)

## Features
- AI-powered meeting summarization (Gemini / Gemma)
- Extracts action items, assignees, due dates
- Syncs tasks to Google Calendar
- Appends entries to Google Sheets
- Sends summary email via Gmail API
- Firestore storage for meeting logs

## Tech Stack
- Frontend: React, OAuth
- Backend: Node.js, Express, Google APIs
- LLM: Gemini API or self-hosted Gemma on Cloud Run GPU
- Deployment: Cloud Run, Artifact Registry, Cloud Build
- Security: OAuth2, Secret Manager

## Setup
- Install dependencies in each folder
- Add environment variables from `.env.example` files
- Deploy services to Cloud Run

