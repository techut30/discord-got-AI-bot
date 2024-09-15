# Discord AI Bot with OpenAI Integration

This repository contains the code for a Discord bot that integrates with OpenAI's GPT-3.5 model. The bot responds to prompts, answers questions, and includes some additional features like basic interactions and commands.

## Features
- **Slash Commands:** Supports various commands such as `/hello`, `/ping`, `/prompt`, `/help`, `/invite`, and `/shutdown`.
- **AI-Powered Responses:** Uses OpenAI's GPT-3.5 to generate responses based on user prompts.
- **Simple Setup:** Customizable and ready for deployment with minimal configuration.
- **Guild Syncing:** Slash commands are synced for specific Discord guilds, ensuring faster availability.
- **Interaction Handling:** Handles basic user interactions and displays helpful responses.

## Setup Guide

### Requirements
- Python 3.8+
- OpenAI API Key
- Discord Bot Token
- Libraries:
  - `discord.py`
  - `openai`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-ai-bot.git
   cd discord-ai-bot

2. # Discord AI Bot with OpenAI Integration

This repository contains the code for a Discord bot that integrates with OpenAI's GPT-3.5 model. The bot responds to prompts, answers questions, and includes some additional features like basic interactions and commands.

## Features
- **Slash Commands:** Supports various commands such as `/hello`, `/ping`, `/prompt`, `/help`, `/invite`, and `/shutdown`.
- **AI-Powered Responses:** Uses OpenAI's GPT-3.5 to generate responses based on user prompts.
- **Simple Setup:** Customizable and ready for deployment with minimal configuration.
- **Guild Syncing:** Slash commands are synced for specific Discord guilds, ensuring faster availability.
- **Interaction Handling:** Handles basic user interactions and displays helpful responses.

## Setup Guide

### Requirements
- Python 3.8+
- OpenAI API Key
- Discord Bot Token
- Libraries:
  - `discord.py`
  - `openai`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-ai-bot.git
   cd discord-ai-bot


2. Install the required dependencies
   ```bash
   pip install -r requirements.txt

### Set up your environment variables:

1. Replace the placeholder `YOUR-BOT-TOKEN` with your actual Discord bot token in `bot.py`:
   ```python
   BOT_TOKEN = "YOUR-BOT-TOKEN"
2. Replace the placeholder YOUR-OPEN-AI-API-KEY with your OpenAI API key in openai_client.py:
   ```bash
   API_KEY = "YOUR-OPEN-AI-API-KEY"

3. Update the GUILD_ID to your server's guild ID in bot.py:
   ```bash
   GUILD_ID = 000000000000000000  # replace with your guild id

4. Make sure to keep your bot token and API key secure and never share them publicly.
   ```bash
   This way, each step is clearly defined, and the code changes are presented in a neat, readable format. The use of code blocks and numbered instructions makes the section more visually appealing and easier to follow.




### Run the bot:
```bash
python bot.py



Commands

Command	Description
/hello	Sends a greeting message.
/ping	Sends a simple ping response with latency.
/prompt	Sends a prompt to the AI and receives a response.
/start	Initializes or reloads the AI conversation.
/invite	Generates an invite link for the bot.
/shutdown	Shuts down the AI model.
/help	Lists all the available commands.



