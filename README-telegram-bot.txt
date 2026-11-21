# Telegram Bot Client

Desktop Telegram bot for receiving and sending messages from a Windows PC. Incoming messages appear in the terminal, and replies can be sent to the latest conversation or to a specific chat.

## Requirements

- Windows
- PowerShell
- Internet connection
- Telegram account

## Getting a bot token

1. Open Telegram and find [@BotFather](https://t.me/BotFather).
2. Send `/newbot` and follow the instructions.
3. Copy the generated bot token.

## Installation and launch

1. Clone or download this repository.
2. Double-click `start-telegram-bot.bat`.
3. At the first launch, enter your bot token when prompted.
4. The token will be saved to `bot-token.txt` for future launches.
5. Keep the terminal window open while the bot is running.

## Usage

- Write a message to the bot in Telegram. It will appear in the terminal.
- Enter text in the terminal and press <kbd>Enter</kbd>. The bot will send it to the latest conversation.
- Use `/to <chat_id> <text>` to reply to a specific chat.
- Use `/chats` to show the known chats.
- Use `/quit` to stop the bot.

## Project files

- `telegram-bot.ps1` — PowerShell bot implementation.
- `start-telegram-bot.bat` — Windows launcher for quick double-click startup.
- `bot-token.txt` — locally stored bot token, created after the first launch.
- `LICENSE` — project license.

## Security

Keep `bot-token.txt` private. Anyone with the token can control the bot.
