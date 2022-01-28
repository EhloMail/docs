---
title: 'Configure Encryption'
media_order: '1. add rule name.PNG,2. filter settings.PNG,3. strip subject line.PNG,wildcard filter.png'
taxonomy:
    category:
        - docs
visible: true
---

If this feature is enabled in your email plan, you can easily configure encryption to be triggered either manually (using trigger tags) or automatically (ie encrypt all email that meets a certain criteria by default). 

There are several ways to use encryption and you can tweak this to meet your organisation's exact needs, but we will showcase two of the most common use cases. 

1. Email subject predefined tags
2. Automatic Encryption using custom rules

### Encryption using Email subject tag

By default, one outbound filter is automatically created with the "[encrypt]" trigger. This means any emails that have "[encrypt]" in the subject will be encrypted. 

If you wish to use a different encryption trigger - e.g [private] , [secure], [sensitive], [topsecret] etc. you can do so following these steps: 

1. Go to Security Settings > Email > Filter Policies > Outbound
2. Click on New Filter.
![](1.%20add%20rule%20name.PNG)
3. Choose a name for your filter (e.g. Encryption - subject).
4. Click Continue.
5. Ensure Scope is set to **Company**.
6. Select "If" statement
* 	First parameter: Email Subject
* 	Second Paraemter: CONTAIN ANY OF
* 	Text box: [encryption trigger]
![](2.%20filter%20settings.PNG)
7. "Do" statement
8. Select Encrypt
9. Click **ADD ANOTHER ACTION**
10. Select **Strip Subject Line Encryption Terms**

![](3.%20strip%20subject%20line.PNG)

11.Click Save.

_**Note**: Entering in multiple key words is fine, but each needs to have a comma and single space to run correctly_

### Automatic Encryption

You can configure encryption to take place automatically whenever an email is sent to a certain recipient or any email accounts belonging to a certain domain. For example, you can force all emails sent to your bookkeepers to be encrypted. 

To do this, the steps are very similar to the ones above, except at step 6. you will need to choose:
* If **Recipient Address** is 
* Add the email address or the whole domain (see screenshot below)
* Do **Encrypt**
* Save
![](wildcard%20filter.png)

You can also use other triggers for automatic encryption, like Message Content, attachment type, email headers, etc. Please also see the next article about DLP policies for more advances automatic encryption rules.