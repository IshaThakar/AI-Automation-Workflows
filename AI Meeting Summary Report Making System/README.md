# AI Meeting Summary Report Generator

An AI-powered automation workflow built with **n8n** that converts meeting transcripts into structured, professional meeting reports. Users simply provide a meeting transcript and a recipient's email address. The workflow analyzes the discussion using an AI model, generates a formatted Google Docs report, and automatically emails it to the specified recipient.

---

## Overview

Manual meeting documentation is time-consuming and often results in missed details or inconsistent notes. This workflow automates the entire process by generating a comprehensive meeting summary from a transcript and delivering it as a shareable Google Document.

---

## Features

- Accepts meeting transcripts as input
- Analyzes transcripts using an AI language model
- Generates a structured meeting summary
- Extracts key discussion points
- Identifies decisions made during the meeting
- Extracts action items and responsibilities
- Creates a formatted Google Docs report
- Automatically emails the report to the specified recipient
- Fully automated using n8n

---

## Tech Stack

- n8n
- AI Language Model (Groq / Gemini / OpenAI Compatible)
- Google Docs API
- Google Drive API
- Gmail API

---

## Workflow

1. The user submits:
   - Meeting transcript
   - Recipient email address

2. The AI analyzes the transcript and extracts:
   - Meeting title
   - Executive summary
   - Key discussion points
   - Decisions made
   - Action items
   - Assigned owners (if mentioned)
   - Deadlines (if mentioned)
   - Next steps

3. A formatted meeting report is created in Google Docs.

4. The document is stored in Google Drive.

5. An email containing the report (or document link) is automatically sent to the provided email address.

---

## Sample Report Structure

```
Meeting Summary

Executive Summary

Key Discussion Points

Decisions Made

Action Items
- Owner
- Task
- Deadline

Risks / Blockers

Next Steps
```

---

## Use Cases

- Team meetings
- Client meetings
- Sprint planning
- Project reviews
- Daily stand-ups
- Brainstorming sessions
- Interview discussions
- Academic meetings

---

## Benefits

- Eliminates manual note-taking
- Produces consistent and professional meeting reports
- Improves accountability through action item tracking
- Saves time and increases productivity
- Simplifies sharing meeting outcomes

---

## Future Enhancements

- PDF export
- Slack and Microsoft Teams integration
- Calendar integration
- Speaker identification
- Multi-language support
- Sentiment analysis
- Automatic meeting title generation
- Integration with Zoom and Google Meet recordings

