---
title: 'Account Email Validation Settings'
taxonomy:
    category:
        - docs
visible: true
---

 EhloMail uses email validation rules to verify that a message is from a valid email address.  For email received to the users who use the advanced EhloMail Web Client (EWC), you can define additional email validation rules as global settings or as domain settings.

1. Navigate to Home > Configure > Global Settings > Advanced **OR** Configure > Domains > Advanced page
2. In the <span style="font-weight: bold;">Regular expression for invalid email address</span> field, enter a regular expression (regex) to filter out the email addresses you consider invalid. 
3. You can add multiple regular expressions.
4. Click Save.

Examples of regular expressions:

*   <span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">test@\\\d+.com</font></span> <span style="font-weight: normal;">identifies email addresses with a number in the domain name as invalid. That is, test@123.com or test@1.com are not valid addresses.</span>
*   <span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">mail@dontallow.com</font></span> <span style="font-weight: normal;">identifies email address that should not be used.</span>

**Note**: Email validation does not work when messages are sent from the standard EhloMail Web Client