# Lead Management Automation

An end-to-end lead management workflow designed to capture, validate, store, follow up, and report on incoming sales leads automatically.

## What the system does

- Receives new leads through a webhook
- Validates required lead information
- Cleans and standardises incoming data
- Stores leads in PostgreSQL
- Prevents duplicate records using email-based UPSERT logic
- Sends an acknowledgement email for new leads
- Runs scheduled follow-up reminders
- Tracks lead status
- Generates SQL-based reporting metrics
- Updates a Google Sheets dashboard

## Workflow Overview

Lead Form / External App
→ Webhook
→ Validation
→ Data Cleaning
→ PostgreSQL
→ Status Check
→ Acknowledgement Email
→ Scheduled Follow-Up
→ Reporting
→ Dashboard

## Key Features

- REST API and webhook concepts
- JavaScript data cleaning
- PostgreSQL
- Parameterised SQL
- UPSERT logic
- Scheduled automation
- Automated email communication
- SQL reporting
- Dashboard updates

## What I Learned

- Webhook-based automation
- REST API concepts
- JavaScript in n8n
- SQL and PostgreSQL
- Database constraints
- Duplicate handling
- Scheduled workflows
- Reporting automation
- End-to-end workflow testing

## Status

Working prototype completed and tested.
