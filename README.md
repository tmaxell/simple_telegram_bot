# simple_telegram_bot
## Features
- **Start Command**: Initiates the conversation by prompting the user for their name and age. </br>
- **Weather Information**: Users can inquire about the weather in a specific city. </br>
- **Currency Exchange Rates**: Users can request exchange rates between different currencies and specify the amount to convert. </br>
- **Text Translation**: Provides text translation functionality, allowing users to translate text to Russian. </br>
- **Error Handling**: Handles unknown commands gracefully by providing guidance on proper command usage. </br>
  
## How to Use
1. Start the conversation by sending the `/start` command. Follow the prompts to provide your name and age. </br>
2. Once the initial setup is complete, you can use the following commands: </br>
   - `/погода`: Get the weather information for a specific city. </br>
   - `/курсы_валют`: Inquire about currency exchange rates and specify the currencies and amount for conversion. </br>
   - `/переводчик`: Utilize the text translation feature by entering the text you want to translate. </br>
3. Follow the prompts and enter the required information or commands to receive the desired information or translations.

## Dependencies
- `aiogram`: Asyncio-based library for Telegram Bot API. </br>
- `python_weather`: Library for accessing weather information. </br>
- `translators`: Library for text translation. </br>
- `forex_python`: Library for currency exchange rate conversion. </br>

## Setup
1. Obtain a Telegram Bot API token from the BotFather on Telegram. </br>
2. Install the required dependencies using pip: </br>
`pip install aiogram python_weather translators forex_python` </br>
3. Replace the `TOKEN` variable value in the script with your Telegram Bot API token. </br>
4. Run the script, and the bot will be operational.
