---
title: 'Catch-all email alias'
taxonomy:
    category:
        - docs
visible: true
---

### What is a domain catch-all address? 

This is a special email address designated to receive all messages that are, either accidentally or purposely, sent to incorrect email addresses belonging to your domain. 

For example, if info@domain.com is set as a catch-all, it will receive any correspondence that was sent to a non existing email account on the domain. This is a handy solution for retrieving emails that were addressed to a misspelled version of an existing email address (eg jonh@domain.com instead of john@domain.com) and would otherwise bounce. 

While this might sound like a good idea, the biggest downside of using domain catch-all is that it enables spammers to send unlimited emails to your account, because the catch-all will just accept the delivery of these emails, regardless if the recipient account exists or not. 

It's well known that spammers try to guess email addresses on target accounts and a common practice among them is to use directory harverst attacks, which means they will send mail to different combinations / variations of email addresses. They then try to figure out which emails are valid by looking at which of these accounts bounce. If you have a catch-all enabled on your domain, all this high volume spam will instead be delivered to your catch-all alias, which will not only flood your account with malicious messages, but also cause load issues on the mail server. 

In order to protect your domain and our platform, catch-all accounts are not allowed in EhloMail. If a user sends an email to a non-existend email address, they will instead receive an undelivered message, allowing them to double check the recipient email and re-send the message.

