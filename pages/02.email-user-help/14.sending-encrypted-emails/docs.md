---
title: 'Sending Encrypted Emails'
media_order: 'encryption recipient.png,encryption send email.png'
taxonomy:
    category:
        - docs
visible: true
---

Your domain administrator will need to configure and advise which triggers you can use but once you have this information, the Email Encryption feature is very straighforward and easy to work with.   

### Email Encryption Overview 

1. Login to your [EhloMail webclient](https:mail.ls) and compose a message as normal 
2. Before sending the email, make sure you add the trigger at the end of the Subject line. We used [private] as a trigger in this example. 
![](encryption%20send%20email.png)
3. The email is sent to the Encryption service (over TLS) where the content is analyzed to determine if there are any filters that apply to the message.
4. An encryption filter is created and applied to the email.
5. The email is delivered and stored in the Encryption portal.
6. You will then receive a separate notification email to confirm the message was encrypted (e.g., "Your email was encrypted").
7. A notification email is also sent to each recipient, to let them know they have encrypted correspondence (e.g., "You have received an encrypted email"). 
![](encryption%20recipient.png)
8. In order to read your message, they will need to click on the link in the email to view the content via the [Encryption portal](https://inbox.proofpoint.com) 
9. The recipient needs to register (one-time) to the service to read the email.
10. The recipient can then reply to the email from the same portal.
11. Their reply is then delivered to your inbox via TLS.