# AI Invoice Automation System

## Description

This project is an AI-powered invoice processing workflow built using n8n, Google Gemini, Gmail, Google Drive, and Google Sheets.

The workflow automatically monitors invoice emails, downloads PDF attachments, extracts invoice information using AI, uploads files to Google Drive, and stores structured invoice data into Google Sheets for automated expense tracking and management.

The system helps streamline invoice processing and reduces manual data entry through intelligent automation.

## Features

* Automated invoice email monitoring
* PDF attachment extraction
* AI-powered invoice data processing
* Google Drive file storage
* Structured Google Sheets integration
* Automated Gmail processing
* Intelligent invoice field extraction
* End-to-end workflow automation

## Workflow Process

1. Workflow monitors incoming invoice emails
2. PDF attachments are downloaded automatically
3. Invoice files are uploaded to Google Drive
4. Google Gemini AI extracts invoice information
5. Structured invoice data is processed
6. Invoice details are stored in Google Sheets
7. Processed emails are marked as read

## Technologies Used

* n8n
* Google Gemini AI
* Gmail API
* Google Drive API
* Google Sheets API
* Workflow Automation

## Core Components

### Gmail Integration

Fetches invoice emails and downloads PDF attachments automatically.

### Google Drive Integration

Uploads and stores invoice files securely in Google Drive.

### Google Gemini AI

Extracts and processes invoice information intelligently.

### Google Sheets Integration

Stores structured invoice records for tracking and analysis.

### Workflow Automation

Handles complete end-to-end invoice processing automatically.

## Workflow Architecture

Email → PDF Extraction → AI Processing → Google Sheets Storage

## Extracted Fields

* vendor
* total_amount
* gst
* invoice_date
* invoice_number
* payment_method

## Project Structure

```bash id="8mx5uc"
PROJECT 1/
│
├── AI AUTO-SAVE GMAIL.json
└── README.md
```

## Setup Instructions

1. Import `AI AUTO-SAVE GMAIL.json` into n8n
2. Configure Gmail API credentials
3. Configure Google Drive credentials
4. Configure Google Sheets credentials
5. Configure Google Gemini API access
6. Activate the workflow
7. Start automated invoice processing

## Use Cases

* Invoice automation systems
* Expense management workflows
* AI-powered document processing
* Automated accounting workflows
* Business process automation
* Financial document management

## Future Improvements

* Expense analytics dashboard
* Vendor analytics system
* Fraud detection workflows
* Database integration
* Multi-format invoice support
* OCR optimization

## Files

* `AI INVOICE AUTOMATION.json` → Main n8n workflow
* `README.md` → Project documentation
