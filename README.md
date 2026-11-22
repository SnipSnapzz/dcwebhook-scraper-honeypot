dcwebhook-scraper-honeypot

## IMPORTANT

If you just happened to stumble into this repository because your snoopy or whatever the fuck it might be, I would appreciate it if you message snipsnapz on discord letting me know and DONT TOUCH THE WEBHOOK!! I understand that sharing this repository may scew the results so keep it on the downlow!!!

## Discord Webhook Monitoring

I have been wanting to do this for a while now. One of the main objectives of this experiment is to determine whether automated repository scrapers discover and attempt to use exposed Discord webhook URLs. I hope to find some fascinating results :D

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
