# Scholarship Eligibility System

## Description

This project is an automated scholarship eligibility workflow built using n8n.

The workflow collects student information through a form submission, evaluates eligibility based on percentage criteria, and automatically sends email notifications to students regarding their scholarship status.

## Features

* Automated scholarship application form
* Student data collection
* Dynamic full name generation
* Percentage-based eligibility validation
* Automated Gmail notifications
* Real-time workflow processing
* Conditional automation logic

## Workflow Process

1. Student submits the scholarship form
2. Workflow captures:

   * First Name
   * Last Name
   * Percentage
   * Phone Number
   * Email ID
3. System formats and processes the student data
4. Eligibility is checked automatically
5. Eligible students receive a confirmation email
6. Non-eligible students receive a rejection email

## Technologies Used

* n8n
* Gmail API
* Workflow Automation
* Conditional Logic
* Webhooks

## Eligibility Logic

* If percentage is greater than 33:

  * Student is marked eligible
  * Confirmation email is sent

* Else:

  * Student is marked not eligible
  * Rejection email is sent

## Project Structure

```bash
PROJECT2/
│
├── SCHOLARSHIP-ELIGIBILITY.json
└── README.md
```

## Setup Instructions

1. Import `SCHOLARSHIP-ELIGIBILITY.json` into n8n
2. Configure Gmail OAuth credentials
3. Activate the workflow
4. Submit the scholarship form
5. Verify automated email responses

## Use Cases

* Scholarship application automation
* Student eligibility validation
* Educational workflow automation
* Automated email notification systems
* Form-based automation pipelines

## Future Improvements

* Database integration
* AI-based eligibility analysis
* SMS notifications
* Admin dashboard
* Multi-criteria validation system

## Files

* `SCHOLARSHIP-ELIGIBILITY.json` → Main n8n workflow
* `README.md` → Project documentation
