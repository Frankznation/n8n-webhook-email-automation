# Webhook to Email Automation (n8n)

## Overview
This project demonstrates a simple but practical automation built with **n8n**.
When a webhook URL is triggered, an email is automatically sent using Gmail.

This project is part of my AI automation learning journey and showcases
event-driven workflow automation.

---

## What This Automation Does
- Listens for incoming HTTP requests via a webhook
- Triggers an automated workflow
- Sends an email notification using Gmail

---

## Tools Used
- n8n (Cloud)
- Gmail (OAuth)
- Webhooks

---

## Workflow Logic
Webhook → Gmail (Send Message)

1. A webhook URL is called
2. n8n receives the request
3. Gmail sends an email notification

---

## Use Cases
- Website contact form alerts
- System notifications
- Simple API event notifications
- Monitoring and alerting systems

---

## How to Use This Workflow
1. Import the `workflow.json` file into n8n
2. Connect your Gmail account
3. Activate the workflow
4. Call the webhook URL to trigger the email

---

## What I Learned
- How webhooks work in n8n
- Difference between test and production modes
- How to connect external services (Gmail)
- How to debug common automation errors

---

## Screenshots
Screenshots of the workflow and successful execution are included in this repository.
