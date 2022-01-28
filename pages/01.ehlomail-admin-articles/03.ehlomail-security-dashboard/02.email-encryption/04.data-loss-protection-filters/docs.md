---
title: 'Data Loss Protection filters'
media_order: '1. add filter.PNG,2. choose smart IDs.PNG'
taxonomy:
    category:
        - docs
visible: true
---

DLP filters allow you to block Data Loss and comply with various Regulatory Policies with a user-transparent, centrally based, policydriven data loss prevention filter. When these are in place, users simply send email, and the appropriate action is automatically taken.

DLP Dictionaries and Smart Identifiers provide automatically updateable policies for lowest administrative cost and highest  accuracy. Always know where your private or proprietary data resides—including intellectual property, personal dentification, patient information, financial information, and more—so you can simplify discovery, and quickly evaluate the data in order to make an appropriate response to any issue.

### How to create a DLP filter to protect privacy data

1. Click **Company Settings.**
2. Click **Filters**.
3. Select the **Outbound** tab.
4. Click **New Filter**.
5. Choose a name for your filter (e.g. Encryption - DLP[term]).
6. Click **Continue**.
7. Ensure **Scope** is set to **Company**.
8. If statement
* First Parameter: Dictionary Scan or Smart Identifier Scan
* Second Parameter: Cannot be changed from "CONTAIN(S) ANY OF"
* Third Paremeter:
* * Click Manage.
![](1.%20add%20filter.PNG)
* * In the pop-up, click the arrow to see the DLP term.
* * Check the box for the appropriate term.
* * Repeat steps above as needed.
![](2.%20choose%20smart%20IDs.PNG)
* * Click Close.
9. Do statement
* Select Encrypt
10. Click **Save**.

**NOTE:**
When selecting DLP, it would be best to use both Dictionary and Smart Identifier Scan to use terms like:

* Smart Identifier: Financial Information > Credit Card Number
* Dictionary: Personal Information > Credit Card Terms
* Utilizing both terms in the same IF statement will help ensure less false positives on a single term being used.

In step 9, it is optional to **Add Another Action**, then also set: Stop Processing Additional Filters.





