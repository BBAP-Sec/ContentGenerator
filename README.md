# Content Generator

![Workflow Preview](./ContentGen.PNG)

## Overview

**DevOps LinkedIn Content Generator** is an automated workflow designed to help DevOps professionals effortlessly craft engaging, relevant, and high-quality LinkedIn posts.

This workflow uses **n8n** to automate the process of:

* Collecting trending keyword suggestions,
* Generating multiple styles of LinkedIn posts using the Gemini API,
* Sending the generated content directly to Telegram for easy review and sharing.

## Features

✅ Fetches live keyword suggestions based on a topic or user input
✅ Generates unique, insightful post drafts with tailored prompts
✅ Supports multiple writing styles to keep content fresh and authentic
✅ Automates delivery via Telegram for instant access

## How It Works

1. **Trigger**: The workflow starts automatically when a new chat message is received or on a daily schedule.
2. **Keyword Extraction**: It queries Google for autocomplete suggestions related to your topic.
3. **Post Generation**: Using Gemini, it creates thoughtful, professional LinkedIn posts customized for DevOps practitioners.
4. **Delivery**: It splits the generated content and sends it directly to your specified Telegram chat.

## Requirements

* [n8n](https://n8n.io/) installed and running
* Google Generative Language API (Gemini) key
* Telegram Bot with API token
* Basic knowledge of setting up credentials in n8n

## Getting Started

1. Clone this repository.
2. Import the `DevOps LinkedIn Content Generator.json` workflow into your n8n instance.
3. Update the API keys and Telegram credentials as needed.
4. Adjust the schedule or triggers to fit your workflow.
5. Start the workflow and receive daily LinkedIn post drafts!

## Preview

See the image above (`ContentGen.PNG`) for a visual overview of how the workflow operates.

---

**Feel free to fork, customize, and improve it for your own professional branding!**
