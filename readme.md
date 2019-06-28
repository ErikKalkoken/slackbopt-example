# slackbot example

This is a minimal example for using slackbot from https://github.com/lins05/slackbot

## Installation

### 1 - Install slackbot package

Your first step is to install the `slackbot` package into your Pyhton environment with:

`pip install slackbot`

### 2 - Create a local folder for your bot

Next create a local folder for all your bot and all its files to live in.

### 3 - Copy files from repo

Copy the following files from this repo to your local folder.:
- `mybot.py`
- `run.py`
- `slackbot_settings.py`

### 4 - Create a Slack app and add a bot user

For your slackbot to work you need to create a Slack app with a bot user. Check out [this post](https://api.slack.com/bot-users#getting_started) on how to create your own Slack app.

Make sure to add a bot user to your Slack app.

### 5 - Install your Slack app into your workspace

Install your new Slack app into your Slack workspace. You can do that directly from the Slack app admin page where you created your app. Go to Oauth & Permissions. page and click on "Install App".

After you installed the app your Slack API tokens will be shown on that page. We would recommend using the "Bot User Oauth Token" (aka "bot token") for your slackbot.

### 6 - Set environment variable for your bot token

Finally you need to give your Python slackbot access to your bot token. For that just set the environment variable SLACKBOT_API_TOKEN to your bot token.


## Run your bot

To run your bot execute the `run.py`.

`$ python run.py`

To test that everything works go to any public channel and try to talk to your bot, e.g.

`@botuser hi`

The bot should reply and also add a thumbs up reaction to your post:

`'I can understand hi or HI!'`

Congratulations! You have completed setting up your slackbot.

Please check out the [official slackbot documentation](https://github.com/lins05/slackbot) to find out how to use all the cool features of slackbot.


