# botkit-apiai-facebook-sample

This is a sample Facebook webhook implementation that integrated [Botkit](https://github.com/howdyai/botkit) and [Api.ai Node SDK](https://github.com/api-ai/api-ai-node-js). This is modified from [facebook_bot.js](https://github.com/howdyai/botkit/blob/master/facebook_bot.js) from [Botkit](https://github.com/howdyai/botkit).

### Usage

#### Install dependencies

```bash
npm install
```

#### Setup environment variables in a `.env` file

```
page_token=<FACEBOOK_PAGE_TOKEN>
verify_token=<FACEBOOK_VERIFY_TOKEN>
apiai_token=<APIAI_TOKEN>
botimize_key=<BOTIMIZE_KEY>
dashbot_key=<DASHBOT_KEY>
subdomain=<SUBDOMAIN>
```

`botimize_key`, `dashbot_key`, and `subdomain` are optional. You can get `botimize_key` and `dashbot_key` at [dashbot](https://dashbot.io) and [botimize](https://dashboard.botimize.io), respectively. `subdomain` is used in `localtunnel` for custome domain.

#### Run your bot command line

```bash
npm run start
```
