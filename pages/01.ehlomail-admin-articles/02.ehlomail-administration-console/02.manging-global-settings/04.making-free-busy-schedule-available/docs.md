---
title: 'Making Free/Busy Schedule Available'
taxonomy:
    category:
        - docs
visible: true
---

The Free/Busy feature allows users to view each other’s calendars for efficiently scheduling meetings. You can set up free/busy scheduling across EhloMail and Microsoft Exchange servers.

EhloMail can query the free/busy schedules of users on Microsoft Exchange 2003/2007/2010 servers and also can propagate the free/busy schedules of EhloMail users to the Exchange server.

To set free/busy interoperability, the Exchange systems must be set up as correctly. See the EhloMail administration guide or contact our support team for help with the Exchange setup requirements.

In addition, the EhloMail global config, Domain, COS and Account settings must be configured.

Procedure

1.  As a global configuration, go to <span style="font-weight: bold;">Configure > Global Settings</span> or for a domain configuration go to <span style="font-weight: bold;">Configure > Domains</span>, select the domain and in the gear icon, click <span style="font-weight: bold;">Edit</span>.

2.  Click <span style="font-weight: bold;">Free/Busy Interop</span> in the Navigation pane.

3.  In the <span style="font-weight: bold;">Microsoft Exchange Server URL</span> text box type the Web interface URL to Exchange.

4.  In the <span style="font-weight: bold;">Microsoft Exchange Authorization Scheme</span> menu select either <span style="font-weight: bold;">Basic</span> or <span style="font-weight: bold;">Form</span>.

*   *   Basic is authentication to Exchange via HTTP basic authentication.

    *   Form is authentication to Exchange as HTML form based authentication.

1.  In the <span style="font-weight: bold;">Microsoft Exchange Server Type</span> menu select either <span style="font-weight: bold;">WebDAV</span> or <span style="font-weight: bold;">ews</span>.

*   *   Select WebDAV to support free/busy with Exchange 2003 or Exchange 2007.

    *   Select ews (Exchange Web Service) to support free/busy with Exchange 2010, SP1.

1.  In the <span style="font-weight: bold;">Microsoft Exchange User Name</span> and <span style="font-weight: bold;">User Password</span>. text boxes, type the name of the account in Active Directory and password that has access to the public folders.

2.  In the  <span style="font-weight: bold;">O and OU used in legacyExchangeDN attribute text box</span> enter the O and OU values that are in the legacyExchangeDN attribute for Exchange. These values correspond to the domain attribute <span style="font-weight: bold;">zimbraFreebusyExchangeUserOrg</span>. When set at the global level, this applies to all accounts talking to Exchange.

To find these values on the Exchange server, you can run the Exchange ADSI Edit tool and search the legacyExchangeDN attribute for o= , ou= , and cn= values.

1.  To check that your settings are correct before you save the configuration, click <span style="font-weight: bold;">Check the settings</span>.

2.  If the configuration is correct, click <span style="font-weight: bold;">Save</span>.  If the configuration is incorrect, click <span style="font-weight: bold;">Clear the Settings</span> to clear all the fields and configure the settings again.

## Setting Up legacyExchangeDN attribute by COS

1.  Go to <span style="font-weight: bold;">Configure > Class of Service</span> and select the COS to set up the free/busy legacy Exchange DN attribute.

2.  Select the <span style="font-weight: bold;">Advanced</span> page, and in the <span style="font-weight: bold;">Free/Busy Interop</span> section

3.  In the  <span style="font-weight: bold;">O and OU used in legacyExchangeDN attribute text box</span> enter the <span style="font-weight: bold;">O</span> and <span style="font-weight: bold;">OU</span> used in the  legacyExchangeDN attribute (i.e. legacyExchangeDN : / o=First Organization/ ou=First Administrative Group)

4.  Click <span style="font-weight: bold;">Save</span>.

## Set up Individual Account's Address

1.  Go to <span style="font-weight: bold;">Manage > Accounts</span> and select the account to edit.

2.  Select the <span style="font-weight: bold;">Free/Busy Interop</span> page.

3.  Click <span style="font-weight: bold;">Add</span>.

4.  In the <span style="font-weight: bold;">Free/Busy Interop Provider</span> drop-down menu, select the interop provider.

5.  In the <span style="font-weight: bold;">Foreign Principal Email address</span> text box enter the account's user's address.

6.  Click <span style="font-weight: bold;">OK</span>. The dialog box closes and the name is added to the Foreign Principals content pane.

7.  Select the address and click <span style="font-weight: bold;">Push</span>.  This schedules the free/busy information to be pushed to the provider and makes the account's free busy status available.

In the individual Accounts>Advanced page you can change the O and OU used for a specific account.  Usually this COS setting is correct.