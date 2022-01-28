---
title: 'Add Foreign Principal Email Address to an Account'
taxonomy:
    category:
        - docs
visible: true
---

The Free/Busy feature allows users to view each other’s calendars for efficiently scheduling meetings. You can [set up free/busy scheduling](/ehlomail-admin-articles/ehlomail-administration-console/managing-email-addresses/manage-account-free-busy-email-address) across ECS and Microsoft Exchange servers.

The EhloMail foreign principal is usually the user's address. This is a multi-value attribute, you can add more than one account address. A prefix is added to the address.  This sets up a mapping from the ECS account to the corresponding object in the Active Directory.

1.  In the <span class="attribute">Free/Busy Interop Provider</span> drop-down menu, select the interop provider.

2.  In the <span class="attribute">Foreign Principal Email address</span> text box enter the account's user's address.

3.  Click <span class="attribute">OK</span>. The dialog box closes and the name is added to the Foreign Principals content pane.

4.  Select the address and click <span class="attribute">Push</span>.  This schedules the free/busy information to be pushed to the provider and makes the accounts free busy status available.