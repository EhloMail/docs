---
title: 'Setting Up Filter Rules'
taxonomy:
    category:
        - docs
visible: true
---

A filter rule consists of one or more conditions and one or more actions. If the message matches the conditions, the specified actions are performed.
You can also set **Activity Stream** rules. Activity Stream rules move messages out of your Inbox into an Activity Stream folder that you can check at your convenience.

### Filter Conditions
A filter can contain one or more conditions. For example, if someone sends you email messages from more than one email address and you want to direct all messages from the person into one folder, you can create one filter that has two conditions, one for each email address, and one action to move the email messages to the same folder.

The order of the conditions is not important. You can choose whether the email message must match all conditions or just meet any one of the listed conditions. You can also use a negative condition. For example, you can filter an email message that does not contain a particular word. Filter conditions are not case-sensitive.

You can base a filter condition on the following:
* Specific email addresses in the From, To, or Cc fields
* Email messages that are under or over a specific size
* Dates
* Presence or absence of file attachments
* Words in the message subject or body
* Calendar invitation
* Email messages that are marked by importance

### Filtering Using Any Versus All
You can group conditions within a filter rule using the terms any or all. The use of these terms is similar to the "AND" versus "OR" type searches described under the Search feature, with any being OR and all being AND.
If you choose any when defining conditions for a new filter rule, then a message that meets any one of the conditions is considered a match. However, if you choose all, every condition specified in that filter rule must apply in order for that message to match the filter.

### Filtering Using Contains, Matches, and Is Options
Three of the comparison methods for filter conditions are **Contains**, **Matches pattern**, and **Matches Exactly**. These options appear for some items such as the subject line. Other comparison methods are available depending on your conditions selections.
* **Contains** means that the specified line must contain, somewhere within it, the specified string. For example, specifying that the subject line contains "bananas" would match both "Cooking with bananas" and "Bananas for breakfast".
* **Matches pattern** means that the specified line must match the specified string, which includes wildcards. For example, specifying " bana*" would match "banana" and "banana tree but not "free bananas".
* **Is** means that the specified line must exactly match the specified string, with no wildcards or substitutions. For example, specifying that the subject line must match "bananas" would only match "bananas" and not "Banana", "My bananas", or "Bananas?"

### Filter Rule Actions
A filter rule can contain one or more actions. If the email message matches the specified conditions, all actions are applied in the order in which they appear in the filter.
* Examples of filter rule actions are:
* Keep the message in your Inbox
* Move the message to a specific folder
* Tag or flag the message
* Discard the message before it reaches your Inbox
* Forward or redirect the message to a specified email address

!! Due to SPF/DKIM limitations, message redirect will only work reliably to other EhloMail-hosted mailboxes.