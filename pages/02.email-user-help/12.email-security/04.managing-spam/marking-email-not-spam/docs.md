---
title: 'Marking Email as Not Spam '
media_order: 'log search proofpoint.png,log search proofpoint2.png,mark email as spam.png,email reported as spam.png,classify as spam.png,report as false negative.png,release from quarantine.png,quarantine digest.png'
taxonomy:
    category:
        - docs
visible: true
---

### From the Quarantine Digests 

These email notifications are designed to allow you to easily view a list of emails that have been quarantined. You can review the digest and choose to take additional actions for each quarantined email. The digest allows you to take the following actions when viewing a quarantined email:
* **Release**: Allows you to release a specific email from a sender one time. This may be an email newsletter that they do not want to receive regularly or an email from a source that you
feel may be a legitimate source. The release function does not update the spam-learning engine and does not create any rules in relation to the sender.
* **Release & Approve**: Allows you to have the desired message released immediately and inform the spam filering to create an **Allow** filter between the sender and recipient so that mail will
not be qualified as **Spam** from this sender in future.

![](quarantine%20digest.png)

_**Note**: Quarantine digests will only include messages that have been quarantined after the last digest was sent._

### From the Email Log

After logging in to your ElhoMail Security dashboard, you will see the **Log Search** screen, where you will be able to find the certain email either by generating a list of quarantined emails, or simply by searching for it based on subject or email address.

You have three options depending on the desired outcome:

* **Release from quarantine** - this will release the selected email(s) from the quarantine and deliver it to its intended recipient.
* **Release and approve** - this will release the selected email(s) from the quarantine and deliver it to its intended recipient. In addition to the step above, the sender will be added to the safe sender list.
* **Classify as clean** - This will inform the spam engine that the selected email is not spam.
* **Report as false positive** - This will launch a new window, which will allow you to:
* * Re-classify the email as false positive
* * Add a comment / explanation
* * Grant permission to the spam team to review the contents of the email
* **Hide email from logs** - This will hide the email from the logs for both users and administrators.

![](release%20from%20quarantine.png)

For oubound emails, you can also **Resend** the message if you are worried it might have not been delivered.
