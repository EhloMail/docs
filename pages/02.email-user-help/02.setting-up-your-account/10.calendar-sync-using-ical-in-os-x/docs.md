---
title: 'Calendar Sync using iCal in OS X'
media_order: '1. add account calendar.png,3. add caldav account.png,4. url username.png,6. new event.png,check calendar name.png,import calendars.png,7. shared calendar .png'
taxonomy:
    category:
        - docs
visible: true
---

This guide will show you how to sync and access all your Calendars using iCal or Calendar in the different OS X versions.

This guide shows you how to access your EhloMail Calendar using OS X and iCal or Calendar. The recommended way to connect your EhloMail Calendar and iCal is using CalDAV. You will synchronize with your EhloMail Server and be able to do all the typical Calendar actions:

* Create appointments
* Edit appointments created from the Web Client or another device
* Delete appointments
* Move appointments
* Dismiss appointments
* etc.

To configure the Calendar, all you need to know is the name of the Calendar you want to sync and add to the URL below:

https://mail.ls/dav/< USERNAME >/CalendarNAME
    
We will explain how to create the Server Address URL:
1. Login to your EhloMail webclient: https://mail.ls and then navigate to Calendar. 
2. Look for the name of the Calendars you have in your account and chose any of your personal calendar names. We will use "Training" as the calendar name and the user tutorials@mail.ls in this example
![](check%20calendar%20name.png)
3. Create your URL in the following way: https://mail.ls/tutorials/Training where tutorials should be your username and Training = the name of your Calendar
4. Now that you have the Server Address the calendar should be imported from, open the Calendar on your Mac. 
5. Add Account 
![](1.%20add%20account%20calendar.png)
6. Select CalDav account
![](3.%20add%20caldav%20account.png)
7. Enter your username, password and server address 
![](4.%20url%20username.png)
8. Sign in

You will now see the new Calendars added to your Mac Calendar and when you create a new event through the Mac Calendar app you will be able to select which account it should be created under. If you want the events to be synced with your @mail.ls user you will have to create it in one of the folders under Mail as in the screenshot below: 
![](6.%20new%20event.png)

## Shared Calendars in Mac Calendar app

The iCal sync feature can also be used for Shared Calendars, not only for personal ones. Let's take an actual scenario to explain how this works: 

Imagine that a Company Director wants to create a separate Calendar for each Team Manager: Sales Manager, Ops Manager and Support Manager, and they need to view the events in their corresponding Calendars and make changes to them. 

The Company Director will need to create three different Calendars: one for each Role. 
![](7.%20shared%20calendar%20.png)
This calendar then needs to be [Shared](http://help.mail.ls/email-user-help/sharing-items/share-calendar) with the team member. For the Sales Calendar for example, permissions will be given to the Sales manager and / or the whole team if appropriate. All the members this calendar has been shared with will receive an invitation to accept the Calendar resource. Once the invitation is accepted, the iCal or the Mac Calendar will sync the Shared Calendar. 

The same steps will then need to be repeated for the other teams.