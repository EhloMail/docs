---
title: 'Setting and Changing Passwords'
taxonomy:
    category:
        - docs
visible: true
---

If you use the EhloMail LDAP directory server for authentication, you can set users passwords. If you use external authentication, passwords are not managed by the EhloMail LDAP server.

It is good practice for the administrator to set at least an initial password when creating accounts. After that, users can change their own passwords based on the password options set up for the account.

Passwords are stored in an encrypted manner in the LDAP directory server. If users forget their password, a new password must be created.

## To set user password

1.  Go to **Manage** > **Accounts** and select the account to edit.

2.  Open  the **General Information** page, enter a new password and re-enter to confirm.

3.  Click **Save**.

4.  Contact the user with the new password.

## To quickly reset a user's password

1.  Go to **Manage** > **Accounts** and select the account to edit.

2.  In the gear icon click **Change Password**.

3.  Enter the new password in the Change Password dialog. Check M**ust change password**, to force the user to change the password upon signing in.

4.  Re-enter the password.

5.  The user must be given the new password manually.