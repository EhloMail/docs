---
title: 'Spoofing protection best practices'
taxonomy:
    category:
        - docs
visible: true
---

## What is email spoofing?## 

Email spoofing is the creation of email messages with a forged sender address (such as your own email address). It is easy to do because the core protocols do not have any mechanism for authentication and it can be accomplished from within a LAN (Local Area Network) or from an external environment.

Spam and phishing emails typically use such spoofing techniques to mislead the recipient about the origin of the message.

## How to prevent spoofing on your domain## 

Adding SPF (Sender Policy Framework) records to your existing DNS information will increase the chances that any spoofed email will be detected and is an extra security measure. When you add an SPF record, all incoming emails will have the sender information validated. Please note that by adding an SPF record does not make this 100% failproof.

The SPF records you need to add to your domain can be found in the [Update DNS records article](http://help.mail.ls/ehlomail-admin-articles/getting-started-admin-guide/update-dns-records)

If you have additional questions about SPF please get in touch with the support team. 

