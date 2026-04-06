# payment-followup-automation
What It Does:
At my part-time job at Katy Violin Shop, staff would manually check for declined payments and follow up with customers one by one. It was a repetitive process that was error-prone and time-consuming.
This workflow automates that process. When a payment is marked as declined in Google Sheets, n8n automatically triggers an SMS notification to the customer, removing the need for manual outreach.

Workflow

How It Works
Trigger — n8n watches the Google Sheets payment log for rows where payment status = Declined
Filter — checks that a follow-up hasn't already been sent for that customer
Action — sends an automated SMS notification to the customer's phone number on file
Log — updates the sheet to mark the follow-up as sent

What I Learned
How to connect APIs across different platforms (Google Sheets + SMS service) using n8n nodes
How to think about business logic as a trigger → condition → action flow
How a small automation can meaningfully reduce manual work in a real business
How to teach myself a new tool from scratch with no prior experience

Why I Built This
This was my first independent automation project. I noticed a real inefficiency at work and figured out a tool to fix it on my own. It's what got me interested in AI workflows and automation more seriously.

Built by Samantha Cui — sophomore at Jordan High School, Fulshear TX
