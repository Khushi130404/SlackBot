# SlackBox

SlackBot is a Django-based bot that integrates with Slack using the Slack Events API. It listens for messages and events in a Slack workspace and responds based on predefined logic.

## Features

- Listens for messages in specific Slack channels.
- Responds to commands and keywords.
- Supports event-driven interactions using the Slack Events API.
- Easily extendable for additional functionality.

## Prerequisites

- Python 3.x

- Django

- A Slack workspace

- A Slack app with Events API enabled

## Setting Up Slack App

- Create a new Slack app from Slack API.
- Enable the Events API and set the request URL to your server (https://yourdomain.com/slack/events/).
- Subscribe to events like message.channels or message.im.
- Add the OAuth & Permissions scope chat:write and channels:history.
- Install the app to your workspace and copy the bot token.
