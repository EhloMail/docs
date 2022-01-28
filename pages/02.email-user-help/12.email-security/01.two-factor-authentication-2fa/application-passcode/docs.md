---
title: 'Application Passcode'
media_order: 'revoke Application_passcode.png,add application code.png,add application code2.png'
taxonomy:
    category:
        - docs
visible: true
---

Clients such as IMAP or ActiveSync do not support the time-based one-time password (TOTP) token required for Two-Factor Authentication. If you are using any of these clients you will need to generate an application passcode instead.

Application passcodes:
* Are randomly generated.
* Can be created by giving a label and revoked by their label.
* Changing account password will revoke all application passcodes.

#### How to create an application passcode

1. Login to your account and navigate to **Preferences** > **Accounts** > **Applications** 
![](add%20application%20code.png)
2. Click on **Add Application Code** button
3. Enter the application name in the **Add Application Code** dialog and click **Next**. 
4. The application passcode will get generated (blured here for security purposes) and it can be used to sign in to your account (instead of your old password).
![](add%20application%20code2.png)

#### How to revoke an application passcode

You can revoke an application passcode by navigating to **Preferences** > **Accounts** > **Applications** in your EhloMail Web Client. Select the required name in the list and click **Revoke Code**.

![](revoke%20Application_passcode.png)