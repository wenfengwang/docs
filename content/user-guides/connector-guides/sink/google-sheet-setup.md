# Google Sheets

This guide contains information to set up a Google Sheets Sink in Vanus Cloud.

## Introduction

Google Sheets is a powerful spreadsheet tool that can be used to store and analyze data. With the Streams menu and Google Sheets Sink connector in Vanus Cloud, you can easily forward real-time updates to a designated sheet in your Google Sheets account, allowing you to track events generated by your application.

## Prerequisites

Before forwarding events to Google Sheets, you must have:

- A Google account with administrative privileges
- A [Vanus Cloud account](https://cloud.vanus.ai)
- A Google Sheets document to which you want to send the events

## Getting Started

**To set up a Google Sheets Sink in Vanus Cloud:**

1. In Vanus Cloud, go to "Sinks" and select "Google Sheets".
2. Click on "Sign in with Google" and follow the process to sign in to your Google account.
![](images/google-sign-in.png)
3. Go to [Google Docs](https://docs.google.com) and create a new Google Sheet.
4. Obtain the Google Sheet ID from the URL. The ID is the long string of characters that comes after the "/spreadsheets/d/" in the URL.
![](images/google-fields.png)
5. Obtain the name of the sheet where you want to store the data.
6. In Vanus Cloud, paste the Google Sheet ID and sheet name into the corresponding fields.
7. Click "Next" to continue.

## Required Data Format

The event data must be in JSON format with the following keys:

```json
{
    "Title": "value",
    "date": "value",
    "ect...": "value"
}
```