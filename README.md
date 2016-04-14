# api-ai-facebook
Facebook bot sources for Api.ai integration

## Deploy with Heroku
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deploy with Docker

```bash
docker run -it --name fb_bot \
           -p <your_desired_port>:5000 \
           -e APIAI_ACCESS_TOKEN="API.AI client access token" \
           -e FB_PAGE_ACCESS_TOKEN="Facebook Page Access Token" \
           -e FB_VERIFY_TOKEN="Facebook Verify Token" \
           xvir/api-ai-facebook
```
