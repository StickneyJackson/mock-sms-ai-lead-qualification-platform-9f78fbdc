# Project Overview

Project Name: Mock SMS AI Lead Qualification Platform

Description: A web application that simulates a SaaS platform for contractors, marketers, and service-based businesses to manage SMS campaigns and qualify leads with AI. The frontend will include mock functionality. This showcases the potential user experience without backend implementation.

Key Sections and Mock Functionality:

Dashboard:
Display total campaigns, leads qualified, messages sent, and (mock) phone number reputation. This provides a high-level overview of the platform's performance.
A navigation sidebar will link to the other sections.

Contact Upload:
Allow users to upload CSV files with contact information. The system will simulate data validation, duplicate detection, and tagging.

SMS Campaign Builder:
Enable users to create and save message templates with variables. They can configure campaign settings (delay, throttle, start/end times). This will include a simulated AI conversation bot attachment.

AI Qualification Bot:
A GPT-powered agent will simulate asking qualifying questions, identifying homeowner intent/interest, and marking contacts as qualified, unqualified, or follow-up.

Chat Inbox:
A live inbox will display simulated ongoing conversations, filtering by campaign, lead status, and bot vs. human assistance. Enable manual takeover of conversations with note/tag assignment.

Training & AI Customization:
A drag-and-drop or form-style editor will simulate modifying AI logic, greeting messages, follow-up sequences, qualification logic, and common objections/responses.

Qualified Leads Feed:
A table view will display mock qualified leads with full name, address, notes from chat, qualification reason, and date qualified. Enable export to CSV, sync to CRM, or send via webhook.

Settings Panel:
Allow users to set company name, reply number, opt-out keywords, compliance settings, and connection settings for SMS API/CRM/AI model fine-tuning.

Technology Stack:
*   Cloudflare next-on-pages framework (NextJS) for the web application frontend.
    <stack>cloudflare-next-on-pages</stack>