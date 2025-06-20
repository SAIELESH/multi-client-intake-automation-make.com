# Multi-Client Intake Automation using Google Forms, Webhooks, Make.com, Google Sheets, ClickUp & Email.

## Overview.

This automation streamlines the end-to-end client intake workflow by integrating Google Forms, Make.com, Google Sheets, ClickUp, and Email. It dynamically routes submissions based on priority, logs entries, assigns tasks, and confirms receipt via email—completely automated and no-code.

## Live Demo

[Open this link for live demo:](https://youtu.be/aABu2LVTKKE)

This demo showcases:

- Google Form submission
- Webhook triggering the Make.com scenario
- Dynamic variable cleanup and routing logic
- Google Sheets logging
- ClickUp task creation
- Confirmation email dispatch

## Workflow Steps

- **1. Google Form Submission**
  - Collects: Client Name, Email, Service Type, Message, Priority

- **2. Webhook Trigger (Make.com)**
  - Captures real-time responses using Google Apps Script and sends data to Make.com

- **3. Tools Module – Set Multiple Variables**
  - Cleans data:
    - Trims whitespace
    - Formats casing
    - Normalizes values

- **4. Router Module – Priority-Based Logic**
  - Routes submissions based on:
    - **High Priority** → Escalation Path
    - **Medium Priority** → Standard Support
    - **Low Priority** → Backlog Queue

- **5. Google Sheets Logging**
  - Logs:
    - Timestamp
    - Name
    - Email
    - Priority
    - Service Type
    - Message
    - Routed Team

- **6. ClickUp Task Creation**
  - Creates internal tasks in ClickUp for the respective team based on priority

- **7. Email Confirmation**
  - Sends an automated email to confirm receipt to the client

## Tech Stack

- Google Forms
- Google Apps Script
- Make.com (formerly Integromat)
- Google Sheets
- ClickUp
- Gmail / Outlook

## Key Benefits

- Instant processing of form submissions  
- Smart team routing via automation  
- Auto-logging for visibility & tracking  
- Fully no-code (fast to deploy)  
- Error-handled and scalable

## Use Cases

- B2B Service Intake
- Tech Support or IT Helpdesk
- Freelance Client Requests
- Consulting Project Onboarding

## Scenario Screenshot.

![image](https://github.com/user-attachments/assets/09847228-497c-44ac-9653-224f2b5557dc)

## Files Included

- `form_to_webhook.js` – Google Apps Script to forward form submissions to Make - present in scripts folder.
- `Client Service Request Intake Form (Responses).xlsx` – Sample responses used for testing.
- `Client intake log.xlsx` - Preprocessed form responses data.
- `client-email-template.md` – Template for confirmation emails.

## Result.
This automation reduced manual processing time by over 90% and helped organize incoming client requests into actionable tasks with zero human intervention.

## Author.
Sailesh Krishnan
