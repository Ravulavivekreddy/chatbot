🤖 Telegram ChatBot – NanBot




NanBot is a simple and friendly Telegram bot built using Python and the python-telegram-bot library. It mimics basic chatbot behavior, responds to user messages, and supports standard Telegram bot commands.

🚀 Features
Responds to greetings and common phrases

Supports commands:

/start – Greets the user

/help – Provides help text

/custom – Example custom command

Works in private and group chats

Handles inappropriate messages politely

Easy to read, extend, and customize

🛠️ Tech Stack
Python 3.10+

python-telegram-bot v20+

📁 Project Structure
bash
Copy
Edit
nanbot/
│
├── main.py             # Core bot functionality
├── README.md           # Project overview and documentation
🔧 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/nanbot.git
cd nanbot
Install dependencies

bash
Copy
Edit
pip install python-telegram-bot==20.*
Configure your bot token

Update main.py with your bot's token and username:

python
Copy
Edit
TOKEN: Final = 'YOUR_TELEGRAM_BOT_TOKEN'
BOT_USERNAME: Final = '@your_bot_username'
⚠️ Warning: Keep your token private. Use .env or other secure methods for production.

Run the bot

bash
Copy
Edit
python main.py
💬 Example Interactions
User Says	NanBot Replies
hello	Hi
how are you?	I am good thanks for asking...
make me laugh	imagine your friend face when teacher asks...
i love you	same i love you much

🤝 Contributing
Want to improve NanBot? Contributions are welcome!

Fork the repo

Create a branch (git checkout -b feature-name)

Make your changes

Commit (git commit -m 'Add new feature')

Push (git push origin feature-name)

Open a pull request

📜 License
This project is licensed under the MIT License.
