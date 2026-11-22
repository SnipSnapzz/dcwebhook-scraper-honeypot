dcwebhook-scraper-honeypot

## Discord Webhook Monitoring

One of the main objectives of this experiment is to determine whether automated repository scrapers discover and attempt to use exposed Discord webhook URLs.

I will use a dedicated webhook to monitor incoming messages.

I will keep track of the following:
- Time to first message.
- Message contents.
- How often I receive messages. 
- General patterns

## Webhook rotation

Obviously it is easy for people to send a DELETE request to the webhook. I will generate a replacement
webhook and update this repository to the best of my ability with a new URL. That way the experiment can
keep running. I will try my best to document each rotation.

No legitimate Discord webhook or production infrastructure is being exposed.
