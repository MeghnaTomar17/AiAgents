
# 🤖 Meeting Insights & Follow-Up Automation Agent

An AI agent that listens to meeting transcripts, summarizes key points, generates personalized to-do lists for each participant, and integrates with Gmail, Google Sheets, and Google Calendar to automate follow-ups.

##  Problem Statement
To eliminate manual effort in tracking meetings, this agent automates:
- Summarization of meetings (via GPT-4o)
- Generation of participant-specific tasks
- Reminders via Google Calendar
- Storage in Google Sheets
- Email follow-ups via Gmail

## Tech Stack
- [n8n](https://n8n.io/)
- Azure OpenAI (GPT-4o)
- Google Calendar API
- Gmail API
- Google Sheets API

##  Workflow Overview
1. Receive meeting transcript via webhook
2. Pass transcript to GPT-4o using Azure API
3. Extract:
   - Summary
   - Personalized to-dos
4. Send:
   - Email via Gmail
   - Append summary to Google Sheets
   - Create Calendar reminders for tasks

## 🔁 AI Prompt Used
