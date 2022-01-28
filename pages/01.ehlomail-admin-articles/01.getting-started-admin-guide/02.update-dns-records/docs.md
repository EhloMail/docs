---
title: 'Update DNS records'
taxonomy:
    category:
        - docs
visible: true
admin:
    children_display_order: collection
---

## Change MX Records for inbound email

In order for inbound messages to be filtered, the DNS MX (mail exchange) records must be properly configured on your domain. Please make sure you update the current MX records to the values below:


| Hostname | Priority |
| ------ | ----------- |
| mx1-eu1.ppe-hosted.com   | 10 |
| mx2-eu1.ppe-hosted.com  | 20 |               	

Don't forget to update your SPF records as well to prevent [domain spoofing](http://help.mail.ls/ehlomail-admin-articles/spoofing-protection-best-practices). Please add the following values to your SPF records to allow mail.ls to send mail on behalf of your domain. 

**v=spf1 include:_spf.mail.ls ~all**

Now that the domain is pointed towards your new email server, let's move on to creating your first email address.

			