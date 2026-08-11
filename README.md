# Daily Task Email Automation

An n8n workflow that automatically sends a daily task list by email at 8:00 AM.

## Workflow

Schedule Trigger → Google Sheets → Python → Gmail

## How It Works

1. The workflow runs automatically at 8:00 AM.
2. It retrieves the daily tasks from Google Sheets.
3. A Python Code node combines the tasks into one message.
4. Gmail sends the task list by email.

## Tools Used

- n8n
- Google Sheets
- Python
- Gmail

## What I Learned

- Building workflows with n8n
- Using Schedule Triggers
- Integrating Google Sheets with n8n
- Processing data using Python
- Working with JSON data
- Automating email notifications

## Workflow Preview

![Workflow Preview](Workflow-1.png)
