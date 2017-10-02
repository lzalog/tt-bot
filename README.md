## Youtrack timetracking bot
### Allows easy time tracking on issues.

You need to export telegram bot token as an environment variable:

	`export TELEGRAM_TOKEN=my_token`

You can choose between 'polling' and 'webhook' modes in docker-compose.yml

For webhook mode, using jwilder/nginx-proxy is recommended.
See an example: https://github.com/MgCoders/docker-wordpress-utils/blob/master/nginx/docker-compose.yml

Uses oficial python client from JetBrains: https://github.com/JetBrains/youtrack-rest-python-library
Uses python-telegram-bot: https://github.com/python-telegram-bot/python-telegram-bot

To run:

    `sudo docker-compose up -d`
