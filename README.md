
# LIZA - AI Chatbot Powered by Google Gemini API and Telegram Bot

This repository contains the implementation of **LIZA**, an AI chatbot integrated with the Google Gemini AI API and deployed on Telegram. LIZA is designed to respond to user queries with helpful and friendly responses, making use of the Gemini model for natural language generation. The bot can also handle general conversations  responding in a sweet and enthusiastic tone with concise and to-the-point answers.

## Features

- **Google Gemini Integration:** Powered by the `gemini-1.5-flash` model from Google Generative AI for generating human-like responses.
- **Telegram Bot Integration:** Handles messages and commands using the Telegram API with Python's `telebot` library.
- **Friendly Conversational Tone:** LIZA responds in a friendly and sweet manner, making interactions pleasant and engaging.
- **Customizable Responses:** The chatbot is designed to answer both short and long questions appropriately and includes suitable emojis when needed.

## Prerequisites

*To run this bot locally, you will need the following:*

1. **Python 3.7+**
2. **Google Generative AI API Key** - For using the Gemini model.
3. **Telegram Bot Token** - Create a bot using [BotFather](https://core.telegram.org/bots#botfather) and get the API token.
4. **Required Python libraries:**
   - `google.generativeai`
     
     run command :
     ```bash
     pip install -q -U google-generativeai
     ```
     
   - `telebot`
     
     run command :
     ```bash
     pip install telebot
     ```


*Follow these steps to set up and run LIZA on your local machine:*

### Step 1: Clone the Repository

First, clone this repository to your local machine using the following command:

 ```bash
 git clone https://github.com/A3x-parvez/LIZA_A.I_Chatbot.git
 ```
### Step 2: Install Required Dependencies
Make sure you have Python 3.7+ installed. Then, install the required Python packages using `pip`

- **Run command :**
 ```bash
 pip install -q -U google-generativeai
 ```

- **Run command:**
 ```bash
 pip install telebot
 ```


### Step 3: Set Up API Keys and Bot Token
Replace the following placeholders in the `app.py` file with your actual API keys and tokens:

`TELEGRAM_BOT_TOKEN`: Your Telegram bot token obtained from BotFather.

`API_KEY`: Your Google Generative AI API key for accessing the Gemini model.

```bash
# Example:
TELEGRAM_BOT_TOKEN = "<YOUR_TELEGRAM_BOT_TOKEN>"
API_KEY = "<YOUR_GOOGLE_GENERATIVE_AI_API_KEY>"
```

### Step 4: Run the Bot
Now that everything is set up, you can run the bot by executing the `app.py` script:
```bash
python app.py
```
The bot will start and begin polling for messages on Telegram.



### Usage

`/start`: Start the conversation with LIZA, and she will greet you with a welcome message.

Input Messages: Send any query or message to LIZA, and she will respond with a thoughtful answer generated by the Gemini AI model.


### Example Interaction:

**User**: "Tell me a fun fact about space!"

**LIZA**: "Did you know that space is completely silent? Since there’s no atmosphere in space, sound has no medium to travel through! 🌌✨"


### Customization
You can customize LIZA's behavior by modifying the `system_instruction` for the Gemini model. For example, you can change her tone, response length, or add new features to the bot.


### Message from the developer -
I am parvez developer of the LIZA . Thank you for visiting my profile and visiting this project repository.❤️
                                
