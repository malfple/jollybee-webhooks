# jollybee-webhooks

Automated contest notifications for discord

## Email services

### Services used:

- https://zapier.com/

### Gmail webhook guide for Zapier:

1. Create a zap: Gmail trigger -> webhook POST command.
2. Set up gmail to listen to specific email.
3. Set webhook to *Custom Request*.
4. Select POST for method.
5. Copy url from discord webhook
6. Use **gmailzapier.json** for data. Note in discord, you can type`\@some_role` to get the role mention command in the form of `<@123xxxsome_numbers>` that can be pasted in the json structure.
7. Add a header`"Content-Type": "application/json`.
8. Test the zap with a sample.

## Helpful Links

- https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks
  - Intro to Discord Webhook 101
- https://gurujsonrpc.appspot.com/
  - Used for testing
- https://leovoel.github.io/embed-visualizer/
  - Discord Embed Visualizer
