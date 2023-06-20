# Bot
#Deploy on heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>
#commands
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users

/stats - checking your bot uptime
#Requirements
API_HASH Your API Hash from my.telegram.org

APP_ID Your API ID from my.telegram.org

TG_BOT_TOKEN Your bot token from @BotFather

OWNER_ID Must enter Your Telegram Id

CHANNEL_ID Your Channel ID eg:- -100xxxxxxxx

DATABASE_URL Your mongo db url

DATABASE_NAME Your mongo db session name

ADMINS Optional: A space separated list of user_ids of Admins, they can only create links

START_MESSAGE Optional: start message of bot, use HTML and fillings

FORCE_SUB_MESSAGEOptional:Force sub message of bot, use HTML and Fillings

FORCE_SUB_CHANNEL Optional: ForceSub Channel ID, leave 0 if you want disable force sub

PROTECT_CONTENT Optional: True if you need to prevent files from forwarding

Extra Variables

CUSTOM_CAPTION put your Custom caption text if you want Setup Custom Caption, you can use HTML and fillings for formatting (only for documents)

DISABLE_CHANNEL_BUTTON Put True to Disable Channel Share Button, Default if False

BOT_STATS_TEXT put your custom text for stats command, use HTML and fillings

USER_REPLY_TEXT put your text to show when user sends any message, use HTML

Fillings

START_MESSAGE | FORCE_SUB_MESSAGE

{first} - User first name

{last} - User last name

{id} - User ID

{mention} - Mention the user

{username} - Username

CUSTOM_CAPTION

{filename} - file name of the Document

{previouscaption} - Original Caption

CUSTOM_STATS

{uptime} - Bot Uptime
