# Termux Deployment Guide

1. Install NodeJS

pkg install nodejs

2. Install PM2

npm install -g pm2

3. Install Dependencies

npm install

4. Create .env file

BOT_TOKEN=your_bot_token_here

5. Start Bot

pm2 start index.js --name xtrench
pm2 save

After restart:

pm2 resurrect
