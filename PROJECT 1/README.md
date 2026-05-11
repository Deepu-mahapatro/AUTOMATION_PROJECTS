# AI Invoice Automation System

An AI-powered invoice processing workflow built using n8n, Google Gemini, Gmail, Google Drive, and Google Sheets.

## Features

* Automatically fetch invoice emails
* Download PDF attachments
* Extract invoice text
* Upload invoices to Google Drive
* Use Gemini AI for invoice data extraction
* Store structured invoice data in Google Sheets
* Mark processed emails as read

## Tech Stack

* n8n
* Google Gemini AI
* Gmail API
* Google Drive API
* Google Sheets API

## Workflow Architecture

Email → PDF Extraction → AI Processing → Google Sheets Storage

## Extracted Fields

* vendor
* total_amount
* gst
* invoice_date
* invoice_number
* payment_method

## Future Improvements

* Expense dashboard
* Vendor analytics
* Fraud detection
* Database integration