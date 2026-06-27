FOR PHONE USER
╔═══════════════════════════════════════════════════════════════════╗
║                                                                   ║
║         🤖 TERMUX MEIN TELEGRAM BOT KAISE CHALAYE 🤖              ║
║                                                                   ║
║                   COMPLETE STEP-BY-STEP GUIDE                     ║
║                                                                   ║
╚═══════════════════════════════════════════════════════════════════╝

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 1: TERMUX INSTALL KARO

• Google Play Store se "Termux" search karo
• Install karo (Latest version)
• Termux open karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 2: TERMUX UPDATE KARO

Termux mein yeh command likho:

pkg update && pkg upgrade -y

Enter press karo - Ho jayega

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 3: STORAGE PERMISSION DO

termux-setup-storage

Enter karo - Allow permission

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 4: PYTHON INSTALL KARO

pkg install python -y

Enter karo - Install ho jayega

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 5: REQUIRED PACKAGES INSTALL KARO

pkg install python-pip git nano -y

Enter karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 6: REQUESTS LIBRARY INSTALL KARO

pip install requests

Enter karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 7: BOT FILE BANAYO

nano bot.py

Enter karo - Editor open hoga

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 8: BOT CODE COPY-PASTE KARO

• Telegram se bot code copy karo
• Termux mein long press karo
• Paste option select karo
• CTRL + X press karo
• Y press karo
• Enter press karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 9: BOT TOKEN CHANGE KARO

nano bot.py

• @BotFather se bot token le lo
• BOT_TOKEN = 'TELEGRAM_BOT_TOKEN_ADD' line dhundho
• Apna token dalo
• CTRL + X → Y → Enter

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 10: BOT RUN KARO

python bot.py

Enter karo - Bot start ho jayega

✅ Bot Started! Polling for updates...

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 11: BACKGROUND MEIN CHALANA

Agar background mein chalana hai toh:

pkg install tmux -y
tmux new -s bot
python bot.py

• Detach karne ke liye: CTRL + B → D
• Wapas aane ke liye: tmux attach -t bot

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📌 STEP 12: BOT KO BAND KARNA

CTRL + C press karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🛠 COMMANDS SUMMARY:

┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  pkg update && pkg upgrade -y    → Update Termux                │
│  pkg install python -y           → Install Python               │
│  pip install requests            → Install requests lib         │
│  nano bot.py                     → Create/edit bot file         │
│  python bot.py                   → Run bot                      │
│  CTRL + C                        → Stop bot                     │
│  CTRL + X → Y → Enter            → Save and exit nano           │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚠️ IMPORTANT TIPS:

✅ Internet connection hona chahiye
✅ Bot token sahi dalna
✅ Termux background mein chal sakta hai
✅ Agar bot band ho jaye toh dubara python bot.py karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

❓ COMMON ISSUES & SOLUTION:

1. "Permission denied" → termux-setup-storage

2. "Package not found" → pkg update && pkg upgrade

3. "Module not found" → pip install requests

4. Bot not responding → Token check karo

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📞 SUPPORT:

Agar koi problem ho toh contact karo: @Cyb3rS0ldier

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🔥 BOT 24/7 ONLINE RAHEGA AGAR TERMUX BACKGROUND MEIN CHALTA RAHE

💎 TOTALLY FREE FOR EVERYONE

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
