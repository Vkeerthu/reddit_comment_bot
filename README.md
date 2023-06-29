
# Reddit Comment Bot
This Reddit Comment Bot is a python-based auto-responder.

Pick a subreddit to scan
Designate a specific comment to search for
Set your bot's reply
Requirements
Python
Praw
A Reddit Account
# Setup
Reddit App:
Navigate to the Apps page
Click create an app
name: Set a name for your app
type: Script
description: Optional
about url: Optional
redirect uri: http://localhost:8080
Note the outputted client id and secret
# config.py:
username: your Reddit username
password: your Reddit password
client_id: the outputted client id
client_secret: the outputted secret
