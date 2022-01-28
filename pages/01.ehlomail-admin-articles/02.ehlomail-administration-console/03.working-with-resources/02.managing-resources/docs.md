---
title: 'Managing Resources'
taxonomy:
    category:
        - docs
visible: true
---

## Managing a Resource Account

A resource account is set up for either a location or piece of equipment that can be scheduled for a meeting. The resource has its own mailbox and can accept or reject invitations automatically based on availability.  The administrator does not need to monitor these mailboxes on a regular basis. The contents of the resource mailboxes are purged according to the mail purge policies.

When you create a resource account, a directory account is created on the LDAP server.

### Procedure

1.  Go to the <span style="font-weight: bold;">Manage > Resources</span> page and in the gear icon select <span style="font-weight: bold;">New</span>.

2.  In the <span style="font-size: 10pt; font-weight: bold;"><font size="2" style="font-size:10pt;">Resource Name</font></span> text box type a descriptive name for the locatio or equipment. The email field is automatically populated with the name. You can change this.

3.  Select the type of resource, either location or equipment.

4.  Select the class of service.  If many resources are going to be created, you might want to set up a separate COS for resources and configure the COS with only the features the resource account needs.

5.  The <span style="font-weight: bold;">Status</span> can be active or unavailable. An active resource can be scheduled. When a resource status is [unavailable](/ehlomail-admin-articles/ehlomail-administration-console/working-with-resources/taking-a-resource-out-of-service), the resource is not included in the resource list.

6.  Check <span style="font-weight: bold;">Auto decline all recurring appointments</span> when the resource can be scheduled for only one meeting at a time, no recurring appointments can be scheduled for this resource.

7.  Set the scheduling policy. The scheduling policy establishes how the resource's calendar is maintained.

<table style="padding-left: 6.00pt; padding-top: 6.00pt; padding-right: 6.00pt; padding-bottom: 4.00pt; margin-left: 18.00pt;" cellspacing="0" width="80%"><colgroup><col width="364"> <col width="576"></colgroup>

<tbody>

<tr style="height: 32px;" bgcolor="#B2B2B2">

<th style="border-top: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;" bgcolor="#B2B2B2">

Option

</th>

<th style="border-top: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;" bgcolor="#B2B2B2">

Description

</th>

</tr>

<tr style="height: 57px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;">

Auto accept if available, auto decline on conflict

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;"><span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">Automatically accept appointments unless the resource is already scheduled. The free/busy times can be viewed. You can modify the auto-decline rule to accept some meetings that conflict.</font></span></td>

</tr>

<tr style="height: 59px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;">

Manual accept, auto decline on conflict

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;"><span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">Appointments that create a conflict are declined. All other appointments must be manually accepted. Appointment requests that do not conflict are marked as tentative in the resource calendar and must be manually accepted. If you use this policy, configure the forwarding address so a copy of the invite is sent to the account that manages this resource. You can modify the auto-decline rule to accept some meetings that conflict.</font></span></td>

</tr>

<tr style="height: 43px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;">

Auto accept always

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;"><span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">The resource automatically accepts all appointments that are scheduled.  In this case free/busy information is not maintained, thus more than one meeting could schedule the resource for the same time. Because the resource always stays free, the suggested use for this policy would be for a frequently used location off premises so that the location address can be included in the invite to attendees.</font></span></td>

</tr>

<tr style="height: 43px;">

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;">

No auto accept or decline

</td>

<td style="border-bottom: solid 1px #000000; vertical-align: top; padding-left: 6.00pt; padding-top: 3.00pt; padding-right: 6.00pt; padding-bottom: 3.00pt;"><span style="font-size: 10pt;"><font size="2" style="font-size:10pt;">The resource scheduling policy is to manually mange the resource. A delegated user logs into the resource account and accepts or declines the reservation request.</font></span></td>

</tr>

</tbody>

</table>

8.  For <span style="font-weight: bold;">Auto accept if available,</span> <span style="font-weight: bold;">auto decline on conflict</span> and  <span style="font-weight: bold;">Manual accept, auto decline on conflict</span>, the scheduling policy can be set up with conflict rules for recurring appointments. You can set up a threshold so that some instances of recurring appointments can be available for this resource. The resource accepts appointments even if there are conflicts until either the number of conflicts reaches the maximum allowed or the maximum percentage of conflicts allowed. In order for partial acceptance of a series to work, both fields must be set to nonzero values.

9.  You can specify the mail server where the resource account is created. The default is to have the resource created on any of the servers listed in the COS server pool.

10.  <span style="font-weight: normal;">In</span> <span style="font-weight: bold;">Forward calendar invitations to these addresses</span><span style="font-weight: normal;">, you can add one or more forwarding addresses of users who manage the resource's Calendar.</span>

11.  Enter the <span style="font-weight: bold;">password</span> for this account.

12.  <span style="font-weight: normal;">In the</span> <span style="font-weight: bold;">Description</span> <span style="font-weight: normal;">text box add a description that can be helpful information about the resource such as room layout, number of occupants, or type of projector, etc. Details in Description are shown to users as a note attached to the resource</span>

13.  Notes can be used to record any type of information. Details in Notes are not exposed to users.

14.  Click <span style="font-weight: bold;">Next</span> to add location information and signature configuration details, or click <span style="font-weight: bold;">Finish</span> to create the resource account.

### Location and Contact Information Page

Resource location includes, site details, capacity and street, city, state address. The information from Building, Floor, and Room fields is automatically populated to the Location Display Name field, if <span style="font-weight: bold;">auto</span> is checked. If auto is not checked, you can enter a location display name.  The content of this field appears as the location information for the resource.

Contact information, including name, email address, and phone number. This information is not exposed to the user.

### Signature Configuration

You can customize the auto response email message.

1.  In the <span style="font-weight: bold;">Name</span> text box enter the name that describes the email message. For example, accept message.

2.  In the <span style="font-weight: bold;">Content</span> text box, type the message that should be sent.

3.  If you are setting up different messages for accept, decline and deny, click <span style="font-weight: bold;">Add Signature</span> and add a new signature and message.

4.  In the <span style="font-weight: bold;">Auto accept signature name</span> menu, select the name of the message that should be sent when accepting a resource request.

5.  In the <span style="font-weight: bold;">Auto decline signature name</span> menu, select the name of the message that should be sent when declining a resource request.

6.  In the <span style="font-weight: bold;">Auto deny signature name</span> menu, select the name of the message that should be sent when denying a resource request.

7.  Click <span style="font-weight: bold;">Finish</span>.

This information can be changed in the resource account.