OSINT Caller Bot
A lightweight Python Telegram bot that retrieves public OSINT data from a remote API.
The bot supports the following lookups:

Number – 10‑digit mobile numbers
Aadhaar – 12‑digit Aadhaar numbers
Family – Linked Aadhaar records
Pincode – 6‑digit postal codes
IFSC – Bank IFSC codes
Instagram – User profile data
Telegram – User IDs or usernames
Vehicle – Registration number
⚠️ Disclaimer
The bot fetches data from a third‑party service. It may contain personal or private information.
Users should not share or publish sensitive data, and the bot’s owners are not responsible for misuse.
🚀 Quick Start
Clone the repository
git clone https:/prajapathitesh037-alt/github.com//osint‑caller‑bot.git
cd osint‑caller‑bot
Create a Telegram bot

Talk to BotFather and create a new bot.
Copy the bot token (e.g., 123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11).
Set the token
Open hitesh.py and replace the placeholder
BOT_TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN_HERE'
with the token you just copied.

Install dependencies
python -m pip install requests
Run the bot
python "c:\Users\<your‑user>\Downloads\OSINTCallerBot Python Script made by Anish Exploits\anish.py"
Leave the PowerShell window open – the bot will keep running until you stop it with Ctrl+C.

📚 Usage
After the bot starts, send /start to the bot in Telegram.
You’ll see a custom keyboard with all the lookup options; tap an option, then send the requested data.

Example:
User: /start
Bot: 📱 NUMBER LOOKUP
User: 9876543210
Bot: ⏳ Fetching details...
Bot: 🔍 <b>NUMBER LOOKUP RESULT</b>
...
🛠️ Configuration
Variable	Description	Example
BOT_TOKEN	Your Telegram bot token	987654321:ABCDEF
API_URL	Base Telegram API URL; auto‑generated from BOT_TOKEN	https://api.telegram.org/bot{BOT_TOKEN}/
If you need to change any endpoint URLs, edit the constants under API Endpoints.

🔐 Security Notice
Do not share the bot token publicly.
Do not use the bot to gather or distribute personal data beyond what is publicly available without consent.
Consider adding exception handling or logging as needed for production use.
🤝 Contributing
Feel free to fork, open issues, or submit pull requests.
Please keep the code within the same style as the existing script.


Happy OSINT‑ing!
