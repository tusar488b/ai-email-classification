# AI Email Classification & Reply Automation

An AI-powered email classification and reply automation workflow built with **n8n** and **Google Gemini**.

## Project Overview

This project analyzes customer emails, identifies their intent and priority, generates an AI-powered reply, and organizes the results in Google Sheets.

## Key Features

- Classifies customer email intent, such as refund requests.
- Assigns priority levels such as HIGH, MEDIUM, and LOW.
- Generates customer-support replies using Google Gemini.
- Extracts structured results from AI-generated JSON.
- Stores email details and AI results in Google Sheets.
- Supports automated email replies through Gmail.

## Workflow

1. Receive customer email data through an n8n Webhook.
2. Analyze the message using Google Gemini.
3. Extract the intent, priority, and suggested reply.
4. Save the results in Google Sheets.
5. Send the reply through Gmail.

## Technologies Used

- n8n
- Google Gemini
- Google Sheets
- Gmail
- Webhooks
- JSON

## Project Status

Built and tested as an AI automation practice project. Further improvements may be made.

## Purpose

To demonstrate practical skills in AI-powered email classification, workflow automation, API integration, and customer-support automation.
