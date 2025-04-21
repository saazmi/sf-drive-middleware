# Salesforce to Google Drive Middleware

This is a simple Node.js server acting as middleware to handle file uploads from Salesforce to Google Drive.

## Features

- Receives file data from a Salesforce component
- Uploads file to Google Drive via Google API
- Returns file URL to Salesforce
- PoC design, modular for future extension

## Stack

- Node.js
- Express
- Google Drive API
- Salesforce (Aura + Apex)

## Usage

1. Clone the repo
2. Run `npm install`
3. Configure Google credentials in `.env`
4. Start server with `node index.js`

## Notes

This middleware is built for a Proof-of-Concept (PoC) and is not production-ready.

