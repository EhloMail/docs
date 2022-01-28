---
title: 'Configuring S/MIME LDAP Settings'
published: false
unpublish_date: '14-01-2020 12:31'
taxonomy:
    category:
        - docs
visible: true
---

If you enabled the S/MIME feature and users use external LDAP servers to retrieve private keys, you must configure the LDAP settings for each external LDAP server that is accessed.

1.  Go to the Configure > Global Settings > S/MIME page.

2.  In the <span style="font-weight: bold;">Configuration Name</span> field, enter a name to identify this LDAP server.

3.  In the <span style="font-weight: bold;">LDAP URL</span> field, enter the LDAP server URL.

1.  To use DN to bind to the external server, in the <span style="font-weight: bold;">S/MIME Ldap Bind DN</span> field, enter the bind DN. If  anonymous bind is used, leave the Bind DN and Bind password empty.

2.  In the <span style="font-weight: bold;">S/MIME Ldap Bind Password</span> field, enter the password to the Bind DN.

3.  To search within a specific branch of the LDAP server, in the <span style="font-weight: bold;">S/MIME Ldap Search Base</span> field enter the search base. For example dc=server,dc=com).

or

Check <span style="font-weight: bold;">Automatically discover search base</span> to automatically discover search base DNs if one is not provided. For this to work, the S/MIME Ldap Search Base field must be empty.

1.  In the <span style="font-weight: bold;">S/MIME Ldap filter</span> field, enter the filter template for the search. The filter template can contain the following conversion variables for expansion:

    *   %n - search key with  @ (or without, if no @ was specified)

    *   %u - with @ removed (For example, mail=%n)

2.  In the <span style="font-weight: bold;">S/MIME Ldap Attribute</span> field, enter the attributes in the external LDAP server that contain the users S/MIME certificates. Multiple attributes can be separated by a comma (,). (For example, "user SM I ME Certificate , userCertificate"

3.  (Optional) Click <span style="font-weight: bold;">Add Configuration</span> to set up another external LDAP server.

4.  Click <span style="font-weight: bold;">Save</span>.