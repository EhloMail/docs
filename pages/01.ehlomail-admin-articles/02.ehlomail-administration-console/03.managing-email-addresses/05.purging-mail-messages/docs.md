---
title: 'Purging mail messages'
taxonomy:
    category:
        - docs
visible: true
---

The email retention policy for email, trashed, and spam messages is set by COS or for individual accounts. The date is calculated from the day the message is received for incoming messages and the day the message was composed for sent messages. The server manages the message purge schedule.

The duration of time that the server should "rest" between purging messages from mailboxes is set in the Global Settings > General Information page. By default, message purge is scheduled to run every 1 minute.

The attributes are set from the Cos for individual accounts.

Procedure

1.  Go to a COS or an account's Advanced page.

2.  In the Email Retention Policy section, set the following lifetimes

<table style="padding-left: 6.00pt; padding-top: 6.00pt; padding-right: 6.00pt; 
		 padding-bottom: 4.00pt; margin-left: 36pt;" cellspacing="0" width="94.831%"><colgroup><col style="width: 28.954%;"> <col style="width: 71.046%;"></colgroup>

<tbody>

<tr style="height: 32px;" bgcolor="#B2B2B2">

<th style="border-top: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;" bgcolor="#B2B2B2">

Option

</th>

<th style="border-top: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;" bgcolor="#B2B2B2">

Description

</th>

</tr>

<tr style="height: 57px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

<span class="attribute">Email Message Lifetime</span>

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

Number of days a message can remain in a folder before it is purged. This includes data in RSS folders. The default is 0; email messages are not deleted. The minimum configuration for email message lifetime is 30 days.

</td>

</tr>

<tr style="height: 59px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

<span class="attribute">Trash Message Lifetime</span>

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

Number of days a message remains in the Trash folder before is purged. The default is 30 days.

</td>

</tr>

<tr style="height: 43px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

<span class="attribute">Spam Message Lifetime</span>

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

 Number of day a message can remain in the Junk folder before it is purged. The default is 30 days.

</td>

</tr>

<tr style="height: 43px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

<span class="attribute">Retention lifetime in dumpster before purging</span>

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; 
			 padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; 
			 padding-bottom: 3.00pt;">

Number of days messages in the dumpster can viewed by the user.  The default is 30 days.

</td>

</tr>

</tbody>

</table>

1.  Click <span style="font-weight: bold;">Save</span>.

<script type="text/javascript" language="javascript1.2">//<![CDATA[ <!-- if (window.writeIntopicBar) writeIntopicBar(0); highlightSearch(); //--> //]]></script>