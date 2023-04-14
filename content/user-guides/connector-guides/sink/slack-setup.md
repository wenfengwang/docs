# Slack

This guide contains information to set up a Slack Sink in Vanus Cloud.

## Introduction

Slack is a cloud-based collaboration platform that allows teams to communicate, collaborate, and share files in real-time. It makes it easier for teams to stay connected and work together more efficiently.

## Prerequisites

Before forwarding events to Slack, you must have:

- A Slack Account
- A [Vanus Cloud account](https://cloud.vanus.ai)

## Getting Started

**To set up an app for receiving events in your Slack channel:**

1. Create an App on Slack
   ![](images/slack-createapp.png)

2. Select From Scratch
   ![](images/slack-selectfromscratch.png)

3. Set the Bot name and Workspace

4. Click on Permissions in the central menu.
   ![](images/slack-clickperm.png)

5. Scopes 'Add OAuth Scope' `chat:write` and `chat:write.public`
   ![](images/slack-setperm.png)

6. Install to Workspace
   ![](images/slack-installworkspace.png)

7. On the left hand menu under "Features" Tab, select **Incoming Webhook**
   ![](images/slack-webhook.png)

8. Scroll down and click "Add New Webhook to Workspace" to add new webhook

9. In Vanus Cloud, select Slack Sink and paste the Webhook URL into the "URL" field.

Click "Next" to continue.

## Required Data Format

The event data must be JSON format, here a simple message, example:

```json
{
  "data": {
    "subject": "Test",
    "message": "Hello Slack!:wave: This is Sink Slack!"
  }
}
```