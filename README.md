# UserBot

# Telegram User Bot

This is a simple Python script for creating a Telegram User Bot using the Telethon library. The User Bot can be used to automate certain actions on your Telegram account.

## Prerequisites

- Python 3.6 or higher
- `telethon` library
- `dotenv` library

## Installation

1. Clone or download the script to your local machine.
2. Install the required dependencies by running the following command:

   `````
   pip install telethon python-dotenv
   ```

3. Create a new `.env` file in the same directory as the script.
4. Open the `.env` file and add the following lines:

   ````
   API_ID=your_api_id
   API_HASH=your_api_hash
   ````

   Replace `your_api_id` and `your_api_hash` with the API ID and hash obtained from [my.telegram.org](https://my.telegram.org/auth).

## Usage

1. Open a terminal or command prompt and navigate to the directory where the script is located.
2. Run the script by executing the following command:

   ````
   python bot.py
   ````

   Replace `bot.py` with the actual name of the script if you have renamed it.

3. Enter your phone number in international format when prompted.
4. You will receive a confirmation code via Telegram. Enter the code when prompted.
5. The User Bot will start and print "User Bot started. Press Ctrl+C to stop." in the console.
6. The User Bot will listen for incoming messages and reply with a predefined message to non-bot senders.

## Customization

You can customize the behavior of the User Bot by modifying the code in the script. For example, you can change the reply message or add additional event handlers to perform different actions when specific events occur.

## Exiting

To stop the User Bot, press `Ctrl+C` in the terminal or command prompt where the script is running.
