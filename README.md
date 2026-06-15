# Fun-Police Discord Bot

A ban-list reference bot for Discord. Shamans can add/remove users, everyone can view the list.

## Commands

| Command | Who | What |
|---|---|---|
| `/banlist` | Everyone | View all banned users |
| `/ban <username> <reason>` | Shaman only | Add someone to the list |
| `/unban <username>` | Shaman only | Remove someone from the list |

## Deploy to Railway (free)

1. Push this folder to a GitHub repo
2. Go to railway.app and sign in with GitHub
3. Click "New Project" → "Deploy from GitHub repo" → pick your repo
4. Go to "Variables" and add:
   - `BOT_TOKEN` = your bot token from Discord Developer Portal
   - `CLIENT_ID` = your Application ID (found on the General Information page of your app)
5. Railway auto-deploys. Your bot will be online in ~1 minute.

## Finding your CLIENT_ID

Discord Developer Portal → Your App → General Information → copy "Application ID"
