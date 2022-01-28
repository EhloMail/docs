---
title: 'Using S/MIME to send and receive email'
published: false
unpublish_date: '14-01-2020 12:32'
taxonomy:
    category:
        - docs
visible: true
---

_**Note**: This feature is only available for certain email plans and can only be used in the Advanced Web Client. If you are not sure if your account has S/MIME feature enabled please contact your domain administrator_

If the S/MIME feature is enabled for your account, you can set up S/MIME to send and receive digitally signed and encrypted messages.
To use S/MIME with EhloMail Enterprise Email, you must have a secure email signing certificate suitable for S/MIME signing and encryption. The certificate with private key must be installed in the local certificate store on a Windows computer, Mac OSX computer, or in the browser certificate store if using Firefox. For information about how to install your certificate see the appropriate computer or browser documentation.

To send and receive encrypted and signed messages, your public key and recipient's public key must be exchanged. To get a copy of a recipient's public key, you can send a digitally signed message using your certificate to the recipient and request that they send you a digitally signed message in reply. When the message is received, the recipient's certificate is stored in the recipient's contact page in Address Book, or a contact is automatically created.

Note the following differences when working with encrypted messages:
* If you are sharing your Inbox, delegated users cannot read your encrypted messages from their computers. Your private key is required to read encrypted messages.
* You cannot run spell check on an encrypted message.
* You cannot search for text in the body or attachments of an encrypted message. Only the header information such as sent to or from, date message was sent, or subject can be found in a search

### Setting Security Preferences for Using S/MIME

If the S/MIME feature is enabled for your account, a **Security** page is available in your **Preferences**.
The default setting for the **Security** preference is to automatically remember the last security option you selected when you composed an email.

You can change the default preference to always send your messages as signed, as signed and encrypted, or to not sign or encrypt your messages. You can change the option from the **Security** tab in the compose page, but the change is only for that message.
1. Click **Preferences**.
2. In the Overview pane, click **Security**.
3. Change the settings.
4. Auto (remember last settings) is the default. The last security option you select is remembered.
5. Select **Do not sign or encrypt** if you do not use the S/MIME feature at all or rarely.
6. Select **Sign** only if you always send your email with a digital signature.
7. Select **Sign and encrypt** if you always send your email encrypted with a digital signature.
8. Click **Save**.