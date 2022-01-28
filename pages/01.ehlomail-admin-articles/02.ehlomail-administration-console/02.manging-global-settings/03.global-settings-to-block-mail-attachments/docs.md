---
title: 'Global settings to block mail attachments'
taxonomy:
    category:
        - docs
visible: true
---

The Attachments tab can be configured with global rules to reject mail with files attached, to convert attachments to HTML for viewing, and to disable viewing files attached to mail messages in users’ mailboxes. When attachment settings are configured in Global Settings, the global rule takes precedence over COS and Account settings.

The attachment settings are as follows:

*   <span style="font-weight: bold;">**Attachments cannot be viewed regardless of COS**</span>. Users cannot view any attachments. This global setting can be set to prevent a virus outbreak from attachments, as no mail attachments can be opened.

*   <span style="font-weight: bold;">**Attachments are viewed in HTML regardless of COS**</span>. Email attachments can only be viewed in HTML. The COS may have another setting but this global setting overrides the COS setting.

*   <span style="font-weight: bold;">**Attachments are viewed according to COS**</span>. This global setting states the COS sets the rules for how email attachments are viewed.

## Selecting extensions to block

Select which file types cannot be viewed. Attachments to messages with these extensions are rejected and the sender gets a bounce notice. The recipient does not receive the mail message and is not notified.  If recipient should receive notification, enable <span style="font-weight: bold;">**Send blocked extension notification to recipient**</span>.

*   Attachments settings can also be set for a Class of Service (COS) and for accounts.

Messages with attachments with blocked extensions are rejected and the sender gets a bounce notice. The recipient does not get the mail message and is not notified.  If the recipient should receive notification, enable **Send blocked extension notification to recipient**.

### If attachment blocking is not enough

*   To temporarily block message delivery to an account, change the [account status](/ehlomail-admin-articles/ehlomail-administration-console/managing-email-addresses/changing-account-status) to "maintenance".

*   To temporarily block message delivery for all accounts on a particular EhloMail mail server, stop mailbox service on that host. Mail will be queued at the MTA until mailbox service is resumed.