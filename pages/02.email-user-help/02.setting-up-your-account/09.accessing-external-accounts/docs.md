---
title: 'Accessing External Accounts'
taxonomy:
    category:
        - docs
visible: true
---

Instead of logging on to each of your external email accounts, you can retrieve email messages from your EMWC account. You can also create a persona to use when you reply to or forward a message received from the external account.

_**Note**: Messages from your external account are not automatically received in your EMWC account. Click the Refresh icon on the toolbar to get the latest messages._

### Add an External Account
1. Go to the **Preferences** > **Accounts** page.
2. Click **Add External Account**.
3. In the **External Account Settings** section, enter the email address of the external account and add a name in the **Account Name** text box to identify the account.
4. Select the type of account: POP or IMAP.
5. In the **Username of Account** text box, enter the name associated with this email account. Sometimes your username is the part of your email address before the @, and other times it is your full email address.
6. In the **Email server** text box, enter the name for your external account’s server.
7. In the **Password** text box, enter the password you use to sign in to the external account. To see that the password you typed is correct, select **Show password**.
8. If your service provider uses a different port than the default, change it in the **Advanced Settings** area. If you use a secure connection, enable **Use an encrypted connection (SSL)** when accessing this server. Your provider should let you know if they do not use a standard IMAP (143) or POP (110) port.
9. Click **Test Settings** to verify the information.
10. Select where to download the messages.
11. To delete messages from the external account after you receive them in your EMWC account, select **Delete messages on the server after downloading them**.
12. Type the name to appear in the **From** field of your outgoing email messages (for example, John). This is the name that is shown before your email address.
13. To direct replies to email messages from this persona to a name and address different from the one you configured in From:
* Select Set the “Reply-to” field of email messages to
* Enter the name in the text box.
14. (Optional) To associate a signature with the persona, click **Manage your Signatures**.
15. Click **Save**.

If you set up a POP account, go to the **Preferences** > **Mail** page to set up how messages in that account should be downloaded to your EMWC account.

### Set Up POP Behavior for Your Account

If you set up an external POP account, you can configure the POP behavior when messages are downloaded to your account.

1. Go to the **Preferences** > **Mail** page.
2. In the Access from Other Mail Clients section, select how to handle messages.
* **Message Downloads** - Select whether to download all mail saved in your POP account to your EMWC account or only new mail received since you set up the access to the external account.
* **Incoming Junk Messages** - Select if you want messages sent to your POP account Junk folder sent to your EMWC account. The messages are added to your POP account folder.
* **Incoming Deleted Messages** - Select how to save messages you deleted in your POP account in your EMWC account.
3. Click **Save**.

### Using Exchange Web Services (EWS)
Exchange Web Services (EWS) provides functionality for EhloMail to communicate with the Exchange Server.

#### Clients Supported for EWS
Client supported include:
* Mac® Outlook 2011
* Mac Native Mail Client

#### Configure Mac Outlook
To configure EWS in Mac Outlook for use with EhloMail Collaboration:
1. Open **Outlook**.
2. Got to **Outlook** > **Preferences** > **Account**
3. Click the **plus symbol (+)** and select **Exchange** from the drop-down menu.
4. Enter your Exchange account **E-mail address**.
5. Select Method **User Name and Password**.
6. Enter your **User name** and **Password**.
7. Uncheck the **Configure automatically** to display this option
8. Enter the EhloMail Server hostname: **mail.ls**
9. Click **Add Account**.

#### Configure Mac Native Mail Client
To configure EWS in Mac Native Mail Client for use with EhloMail Collaboration:
1. Open **Mail Client**.
2. Got to **Mail** > **Preferences**
3. Click the **plus symbol (+)**
4. Enter your **Full Name**.
5. Enter your **E-mail address** and **Password**.
6. Click **Continue**.
7. Select **Exchange** from the drop-down menu.
8. Enter the EhloMail Server hostname: mail.ls