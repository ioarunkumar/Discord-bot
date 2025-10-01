# Discord Admin Bot

## Features
- Notify admin when a new member joins (with DM fallback to a server channel)
- Give roles to members
- Broadcast messages to members with a specific role
- List members in a specific role
- Runs 24/7 using Render with a tiny web server

## Setup
1. Create a Discord bot in the Discord Developer Portal
2. Copy the bot token
3. Invite the bot to your server with Administrator permissions
4. Add your bot code to GitHub
5. Connect your repository to Render
6. Set Environment Variables on Render:
   - DISCORD_TOKEN
   - ADMIN_ID
   - FALLBACK_CHANNEL_ID
7. Start Command: python bot.py
