---
title: 'Changing account status'
media_order: 'change account status.png'
taxonomy:
    category:
        - docs
visible: true
---

Account status determines whether users can log in and receive mail. The account status can be viewed in the Account list shown on content pane or from individual accounts, General Information tab.

The following account statuses can be set

*   <span style="font-weight: bold;">Active</span>. Active is the normal status for a mailbox account. Mail is delivered and users can log into the client interface.

*   <span style="font-weight: bold;">Maintenance</span>. When a mailbox status is maintenance, login is disabled and mail addressed to the account is queued at the MTA.

*   <span style="font-weight: bold;">Locked</span>. When a mailbox status is locked, the login is disabled until you unlock the account, but mail is still delivered to the account. <span style="font-weight: bold;">Locked</span> can be set if you suspect that a mail account has been hacked or is being used in an unauthorized manner. Alternatively, if you have configured **account lockout** rules and users enter the wrong password more than the allowed attempts when logging in, they are temporarily locked out of their accounts.

*   <span style="font-weight: bold;">Closed</span>. When a mailbox status is closed, the login is disabled. This status is used to soft-delete an account. The account exists until you delete it.

*   <span style="font-weight: bold;">Pending</span>. When a mailbox status is pending, login is disabled and mail cannot be received.

###### Procedure

1.  Go to Manage > Accounts.

2.  Select the account to edit and in the gear icon click <span style="font-weight: bold;">**Edit**</span>.

3.  Click the <span class="attribute">General Information</span> page.

4.  From the <span class="attribute">Accounts Setup</span> list, select the desired status.

5.  Click <span style="font-weight: bold;">**Save**</span>.

![](change%20account%20status.png)

The new account status takes effect immediately.