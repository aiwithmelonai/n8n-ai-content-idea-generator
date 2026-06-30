# n8n-ai-content-idea-generator
n8n-ai-content-idea-generator automation workflow
# AI Content Idea Generator

An n8n automation that connects to the Claude API to generate 
YouTube video ideas based on any topic you provide.

Built by [MELON AI](https://aiwithmelonai.com)

---

## What It Does

1. You provide a topic
2. n8n sends it to Claude API
3. Claude returns 5 structured video ideas
4. Results are ready to use immediately

## Tech Stack

- n8n (workflow automation)
- Anthropic Claude API (claude-sonnet-4-6)
- HTTP Request node

## Workflow Preview

<img width="1919" height="912" alt="Screenshot 2026-06-29 233643" src="https://github.com/user-attachments/assets/aae83262-00d4-4a7a-81d8-380dc9266f3c" />


## Setup

1. Import the workflow JSON into n8n
2. Add your Claude API key as a Header Auth credential
3. Update the topic in the Set node
4. Click Test Workflow

## Example Output

Here are 5 YouTube video ideas about AI automation for beginners:\n\n1. **"Automate Your Email in 10 Minutes with AI"** - A step-by-step tutorial showing beginners how to use tools like Zapier and ChatGPT to automatically sort, respond to, and organize emails.\n\n2. **"5 Boring Tasks You Can Automate Today with Zero Coding"** - A practical walkthrough demonstrating how non-technical users can eliminate repetitive daily tasks using free AI tools.\n\n3. **"I Automated My Social Media for a Week - Here's What Happened"** - A personal experiment video showing beginners exactly how to set up AI tools to schedule, write, and post content automatically.\n\n4. **"The Beginner's Guide to Make.com: Build Your First AI Workflow"** - A friendly introduction to Make.com that teaches complete beginners how to connect apps and create their first automated workflow in under 30 minutes.\n\n5. **"ChatGPT + Google Sheets = The Ultimate Automation Hack"** - A beginner-friendly tutorial showing how to combine ChatGPT with Google Sheets to automatically generate reports, summaries, and data analysis.

---

Made with 🍈 by MELON AI
