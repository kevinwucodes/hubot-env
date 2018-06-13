# Hubot

## Configuration

* Create a `.env` file in this repo's root directory so that it contains the following:
```sh
export HUBOT_SLACK_TOKEN=your-hubot-slack-oauth-token-here
export APIGEE_USERNAME=your-apigee-username
export APIGEE_PASSWORD=your-apigee-password 
```

```sh
# Load environment specific environment variables
if [ -f .env ]; then
  source .env
fi
```

## Development


## Deploying to Google App Engine Standard Environment

