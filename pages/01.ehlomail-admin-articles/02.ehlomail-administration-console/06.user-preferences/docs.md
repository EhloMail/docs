---
title: 'User Preferences'
taxonomy:
    category:
        - docs
visible: true
---

How mailboxes behave when a message is composed or received are preferences that are enabled in the COS. The preferences in the COS become the default settings for accounts.

The COS default preferences can be changed for individual accounts, and users can modify their preferences from the EhloMail Web Client Preferences tab.  The account's preferences are updated when users change their options in the Web Client.

The following preferences can be configured.

|General Options|  
| ------|
|**Login using** specifies which version of the EhloMail Web Client is viewed when the user logs in. The options are Advanced and Standard and the user can change this setting before they log in.|
|When **Show search string** is enabled, the search field shows the query grammar used to create the search.|
|**Initial mail search** specified which folder in the mailbox to search first. The default is the Inbox.|
|**Enable keyboard shortcuts**. Allows users to use keyboard shortcut keys.|
|**Display a warning** when administrators try to navigate away from EhloMail Administration Console. **When display a warning** is enabled, users will see a message when clicking the browser Back button to try to navigate away from the EhloMail web console. You can enable a similar warning when administrators click the back button to navigate from the administration console.|
|**Show selection checkbox for selecting email and contact in a list view for batch operations**. This makes it easy for users to select multiple items in the Content pane and perform an action such as move, delete, forward, tag, or mark as read/unread.|
|**Index Junk Messages**.  This is enabled by default.  If you do not want spam to be indexed, disable this message. Users cannot change this.|
|**Language**. Select the default language that will display in the  EhloMail Web Client view.  If no locale is selected, the browser setting is used.|

|General Options for Standard (HTML) client|
| ------ | 
|**Maximum number of items to display per page**.This is the maximum number of messages or conversations that can be displayed on a page in the standard web client.|
|**Number of items to display per page**.This is the number of items that are displayed on a page in the standard web client. This number cannot exceed the maximum number of items to display setting.|

|Mail Options|
| ------ | 
|**View mail as HTML** (when possible).|
|**Display external images in HTML mail**. If this is enabled, images sent in an email are displayed.|
|**Group mail by** Conversation (default) or Message.|
|**Default Charset for mail composing and parsing**. The default is UTF-8\. You can select another default charset form the list. Users have an additional preference that lets them adjust the default font size when printing an email message.  The default is 12 points. This configuration is not in the administration console.|

|Receiving Mail|
| ------ | 
|The following email alerts can be enabled:
|_Play a sound when a message arrives_. This enables a beep sound to play when new emails arrive in the Inbox.|
|_Highlight the Mail tap when a message arrives_. The Mail tab is highlighted when new mail arrives if the user is not working in the Mail tab|
|_Flash the browser title when a message arrives_. When new email arrives, the browser flashes until users open the Mail tab.|
|**Polling interval** This is the number of minutes to wait before checking for new mail. The default is 5 minutes.|
|**Minimum mail polling interval** limits the user's setting their polling frequency.|
|**Out of office cache lifetime** When **Away message enabled** is checked, a reply message is sent to received messages only once during the cache lifetime.  The default is one time every 7 days.|
|**Send read receipts** When the Read Receipt feature is enabled, **Send read** receipts preference sets the default behavior for the recipient of the read receipt message.  Users preferences can be set to **never** send a receipt, **always** send a receipt, or **prompt** before sending a receipt.|

|Sending mail|
| ------ |
|**Save to sent**. A copy of messages that are sent from the account are automatically saved to the Sent folder.|
|**Allow sending email from any address**. Used with Mail Identities to allow users to create different email addresses. If this is not checked users can only select from email addresses or aliases that you configured.|

|Composing mail|
| ------ |
|**Composing Mail** section lets you define the initial user experience when writing an email message. You can set it up to compose messages as Text or HTML, set the font, size and color to use, and **Always compose in new window** displays the compose page in a new window.|
|**Reply/Forward using format of the original message** Check this box to reply to the message in the same format as received. This is useful to make sure the recipient can get the message in the best format they can read.|
|**Enable Mandatory spell check** Mail is spell-checked automatically before it is sent. The default is not enabled.|
|**Signature style**, either Internet standard, with the signature at the end of the message thread or basic, with the signature at the end of the new message.You can configure the signature length. The maximum length of a mail signature is 1024 characters.|
|**Draft auto save interval** Messages that users compose are automatically saved as a draft based on this setting. The default is to save a draft every 30 seconds. Users cannot modify the time, but they can turn off the feature to automatically save drafts while composing.|

|Address Book Options|
| ------ |
|Use GAL when autocompleting addresses. The default is not enabled.|
|Enable automatic adding of contacts.|

|Calendar Options|
| ------ |
|**Time zone** is used to set the default time zone for new accounts in this COS. The time zone you set during the install sets the default COS time zone. See [Setting time zones for accounts](/ehlomail-admin-articles/ehlomail-administration-console/managing-email-addresses/setting-time-zones-for-accounts).|
|**Number of minutes before an appointment to show reminder** The default is 5 minutes.|
|**Calendar views**|
|_Initial calendar view_. This is default view for all users. Work Week is the default.|
|_First day of week_. Specifies which day of the week should be the first day of the week in the calendar. Sunday is the default.|
|**Default appointment visibility**. This can be either Public or Private. Public is the default, all incoming calendar invites are marked as Public unless the creator marked the meeting notification as private. When this is set to Private, all incoming calendar invites are marked as private.|
|**Use iCal delegation model for shared calendars for CalDAV interface**. Apple iCal can be configured to access user calendars using the CalDAV protocol. When this is enabled, shared calendars are displayed in the iCal Account's Delegation tab on an Apple Mac computer. When this is disabled, all shared calendars display in the EMWC Calendars list. This feature is available to be used with iCal 4.0 or later.|
|**Enable past due reminders**.When this is enabled the user's Preferences> Reminders page is displayed. Users configure the email address on this page where they want reminder email message sent for tasks or meetings. Users enable **Send Email** on a task page or a meeting on Calendar and set a date and time to send the reminder message.|
|**Set up Calendar alerts**. Users will be able to receive appointment reminder alerts when EMWC is opened.|
|_Flash browser title on appointment reminder_|
|_Enable audible appointment notification_|
|**Enable toaster notification for new mail**. When this is enabled, a popup displays in EMWC when new calendar events re received.|
|**Allow sending cancellation email to organizer**. When this is enabled, invites have the option to notify the organizer when they delete a meeting from their calendar.|
|A**utomatically add invites with PUBLISH method**. A calendar invitation email should have method=REQUEST in the calendar object, but some third-party email clients incorrectly set method=PUBLISH.  These email messages are not processed as invitations by default.  You can relax the rules by enabling this option.|
|**Automatically add forwarded invites to calendar**. Invites that are forward to users are added to the forwarded user's calendar.|
|**Auto-decline invites** from users who are denied from inviting this user. Users can configure who can send them messages invites in their Calendar preferences. When Auto-decline invites is enabled, an auto-reply message is sent to those users to let them know they do not have permission to invite the user.|
|**Automatically add appointments when invited**. When users receive a meeting invitation, the meeting is added to the default Calendar and marked New.|
|**Notify of changes made via delegated access**. When users share their calendar, and the grantee makes changes to the shared calendar, the grantor is notified of the change.|
|**Always show the mini-calendar**. A mini-calendar always displays in the lower left corner of the Web client.|
|**Use the QuickAdd dialog** when creating new appointments. If the Calendar feature is enabled, users can click on a date to open the QuickAdd dialog to create an appointment.|
|**Show timezone list in appointment view**. The time zone list displays when users create appointments. Users can change time zones when they set up meetings.|