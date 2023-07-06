# Inspirational Quote Bot
The Inspirational Quote Bot is a Discord bot developed in Python. It responds to user requests with inspirational quotes to uplift their spirits. Additionally, it provides the functionality to add custom encouraging messages and toggle the bot's response.

# Features
Generates random inspirational quotes using the ZenQuotes API.
Responds to specific keywords, such as "sad" or "depressed," with uplifting messages.
Allows users to add their own encouraging messages to the bot.
Supports deleting custom encouraging messages.
Provides a list of all custom encouraging messages.
Enables toggling the bot's response on or off.

# Dependencies
The bot requires the following dependencies:

discord: A Python library for creating Discord bots.
requests: A library for making HTTP requests to the ZenQuotes API.
json: A library for working with JSON data.
random: A library for generating random elements.
replit: A library for accessing the Replit database.
keep_alive: A module that keeps the bot running on Replit's servers.
Install these dependencies using the following command:

pip install discord requests replit

# Getting Started
To use the Inspirational Quote Bot, follow these steps:

Clone the repository or download the code files.
Install the required dependencies.
Obtain a Discord bot token from the Discord Developer Portal.
Set the Discord bot token as an environment variable named TOKEN.
Run the main.py file.

python main.py

# Usage
Once the bot is running and connected to your Discord server, you can interact with it using the following commands:

$inspire: Generates a random inspirational quote and displays it in the channel.
$new [message]: Adds a new custom encouraging message to the bot.
$del [index]: Deletes a custom encouraging message based on its index.
$list: Displays a list of all custom encouraging messages.
$responding [true/false]: Toggles the bot's response on or off.
Contributing
Contributions to the Inspirational Quote Bot are welcome! If you have any ideas, suggestions, or bug reports, please submit an issue or create a pull request on GitHub.

# License
The Inspirational Quote Bot is open-source software released under the MIT License. Feel free to modify and distribute the code as per the terms of the license.

# Acknowledgments
The Inspirational Quote Bot utilizes the ZenQuotes API to retrieve random inspirational quotes.
That's it! You now have a README file that explains the purpose and usage of your Discord bot. Feel free to modify it as per your requirements and add any additional sections or information that you think would be relevant.