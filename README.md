# Firestore Document Management and Telegram Notification

This Python script automates the process of deleting documents from a Firestore collection and notifies the user via Telegram. It also scrapes a job listing website and updates the Firestore database with new job postings.

## Features

- Deletes documents from a specified Firestore collection.
- Sends Telegram notifications on successful deletion and completion of tasks.
- Scrapes job listings from a website and updates them to Firestore.
- Uses BeautifulSoup for web scraping and Telepot for Telegram bot interactions.

## Prerequisites

Before running this script, ensure you have the following installed:
- Python 3.10 or above
- Firebase Admin SDK
- BeautifulSoup4
- Telepot
- Requests

## Setup

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Place your Firebase service account JSON file in the project directory and rename it to `service.json`.

## Usage

To run the script, execute the following command in the terminal:

```bash
python web.py
