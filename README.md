# botkit-dashbot-apiai-facebook-sample

This is a sample Facebook webhook implementation that integrated [Botkit](https://github.com/howdyai/botkit), [Dashbot](https://github.com/actionably/dashbot), and [Api.ai Node SDK](https://github.com/api-ai/api-ai-node-js). This is modified from [facebook_bot.js](https://github.com/howdyai/botkit/blob/master/facebook_bot.js) from [Botkit](https://github.com/howdyai/botkit).

### Usage

Run your bot command line:

```bash
page_token=<FB_PAGE_TOKEN> verify_token=<FB_VERIFY_TOKEN> apiai_token=<APIAI_TOKEN> dashbot_key=<DASHBOT_KEY> node facebook_bot.js [--lt [--ltsubdomain LOCALTUNNEL_SUBDOMAIN]]
```

Use the `—lt` option to make your bot available on the web through localtunnel.me.