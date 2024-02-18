"""
# FastAPI Mail Server

This is a simple FastAPI application for scheduling and sending emails asynchronously.

## Getting Started

### Prerequisites

Make sure you have Python installed. You can install the required dependencies using:

```bash
pip install -r requirements.txt


uvicorn app.main:app --host 127.0.0.1 --reload

GET /

POST /send-email

{
  "to": "recipient@example.com",
  "subject": "Your Subject",
  "content": "Email Content"
}

{
  "status": 200,
  "message": "Email has been scheduled"
}

