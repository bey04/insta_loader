# Instagram Video Downloader Bot

A simple Telegram bot that allows users to download Instagram videos by providing a video link. Built using the `python-telegram-bot` library and `instaloader` for Instagram interaction.

---

## Features
- Responds to the `/start` command with a welcome message.
- Accepts an Instagram video link from the user.
- Downloads the video and sends it back to the user directly in the Telegram chat.
- Automatically cleans up downloaded files after sending.

---

## Requirements
To run this bot, you'll need the following:
- Python 3.7 or later
- A Telegram bot token (obtainable from [BotFather](https://core.telegram.org/bots#botfather))
- Required Python libraries:
  - `python-telegram-bot`
  - `instaloader`

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/instagram-video-downloader-bot.git
   cd instagram-video-downloader-bot

