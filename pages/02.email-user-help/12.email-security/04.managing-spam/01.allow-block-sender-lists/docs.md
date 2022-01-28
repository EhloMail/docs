---
title: 'Allow / Block Sender Lists'
taxonomy:
    category:
        - docs
visible: true
---

A sender list is a list of approved or blocked senders. Entries in the list allow or quarantine specific email addresses and/or domains.

Sender lists support the following entries:
* Domains: e.g "*@domain.com" 
* Email Addresses: e.g name@domain.com
* IP Addresses
* * 10.20.0.4
* * 10.20.*.4
* * 10.*.*.*
* * *.20.*.4
* * 10.0.62.0/24

In instances where a single message contains competing actions the following priority logic is used to determine the appropriate action: 
* IP Address > Email > Wildcard Domain > Wildcard IP > IP (CIDR)

### Add entry to Organization Safe Sender List
1. Login to your [EhloMail Security dashboard](https://eu1.proofpointessentials.com/app/login.php?eid=10109)
2. Click on the **Allow / Block Sender Lists** tab.
3. Enter the address or domain into the **Safe Sender List** text area. You can add multiple entries by using a comma, semi-colon or one per line.
4. Click **Save**.

### Add entry to Organization Blocked Sender List
1. Login to your [EhloMail Security dashboard](https://eu1.proofpointessentials.com/app/login.php?eid=10109)
2. Click the **Allow / Block Sender Lists** tab.
3. Enter the address or domain into the **Blocked Sender List** text area. You can add multiple entries by using a comma, semi-colon or one per line.
4. Click **Save**.