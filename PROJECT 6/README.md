# AI LinkedIn Post Automation

## Description

This project is an AI-powered LinkedIn content automation workflow built using n8n.

The workflow automatically generates professional LinkedIn posts using Google Gemini AI, creates AI-generated hashtags, generates cinematic AI visuals, uploads generated images to Google Drive, and sends complete LinkedIn-ready content directly through Gmail.

The system helps automate social media content creation, developer branding, and professional AI-powered LinkedIn posting workflows.

## Features

* Automated scheduled content generation
* AI-powered LinkedIn post generation
* Professional hashtag generation
* AI-generated cinematic visuals
* Automated Google Drive image upload
* Gmail content delivery
* Dynamic AI prompt engineering
* Real-time workflow automation
* Automated LinkedIn content pipeline

## Workflow Process

1. Schedule trigger automatically starts workflow

2. Workflow stores:

   * Topic
   * Audience
   * Tone
   * Platform
   * Content Type

3. Google Gemini AI generates professional LinkedIn content

4. Workflow formats and cleans generated content

5. AI generates optimized LinkedIn hashtags

6. AI creates cinematic image prompts

7. Pollinations AI generates LinkedIn visuals

8. Generated images are uploaded to Google Drive

9. Gmail automatically delivers complete LinkedIn content package

## Technologies Used

* n8n
* Google Gemini API
* Pollinations AI
* Gmail API
* Google Drive API
* Workflow Automation
* AI Prompt Engineering
* HTTP Requests
* JavaScript

## AI Automation Logic

* Daily workflow trigger starts automation

  * AI generates professional LinkedIn content
  * AI creates optimized hashtags
  * AI generates cinematic image prompts
  * Pollinations AI creates LinkedIn visuals
  * Google Drive stores generated assets
  * Gmail delivers final LinkedIn-ready content

* Dynamic prompts improve content quality and formatting

## Project Structure

```bash
PROJECT6/
│
├── AI-LINKEDIN-POST.json
└── README.md
```

## Setup Instructions

1. Import `AI-LINKEDIN-POST.json` into n8n
2. Configure Google Gemini API credentials
3. Configure Gmail OAuth credentials
4. Configure Google Drive credentials
5. Activate the workflow
6. Configure scheduling time
7. Verify automated content delivery

## Use Cases

* LinkedIn content automation
* AI-powered personal branding
* Developer content generation
* Professional social media automation
* Educational AI content workflows
* Automated content marketing
* AI-generated developer posts
* Social media workflow automation

## Future Improvements

* Multi-platform posting support
* LinkedIn API integration
* Analytics dashboard
* AI content personalization
* Multiple image style generation
* Database integration
* Team collaboration support
* AI content scheduling optimization

## Files

* `AI-LINKEDIN-POST.json` → Main n8n workflow
* `README.md` → Project documentation
