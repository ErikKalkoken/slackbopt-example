# slackbot example

This is a minimal example for using slackbot from https://github.com/lins05/slackbot

## Installation

1 - Install slackbot into your Pyhton environment with:
`pip install slackbot`

2 - Create a local folder for your bot with all its files to live in

3 - Copy the following files from this repo to your local folder:
- `mybot.py`
- `run.py`
- `slackbot_settings.py`

4 - Create a Slack app and add a bot user
Check out [this post](https://api.slack.com/bot-users) on how to create a Slack app with a bot user.

5 - Install your Slack app into your workspace and get your token
You can install your new Slack app by clicking on "Install App" on your Slack app management page under Oauth & Permissions.
After you installed your app your tokens will be shown on that page. We would recommend using the "Bot User Oauth Token" for your slackbot

6. Set environment variable for your bot token
You want to set the environment variable SLACKBOT_API_TOKEN to your bot token. Your bot token is a string that looks like this:
`xoxb-123456789-abcdefghijklmnopqrstuvwx' 


## Run your bot
To run your bot execute the `run.py`.
`$ python run.py`

To test that everything works go to any public channel and try to talk to your bot, e.g.
`@botuser hi`

The bot should reply and also add a thumbs up reaction to your post:
`'I can understand hi or HI!'`

Congratulations! You have completed setting up your slackbot.

Please check out the official slackbot documentation to find out how to use all the cool features of slackbot.


