---
title: 'Manage domain authentication settings '
taxonomy:
    category:
        - docs
visible: true
---

The Domain > Authentication page shows the authentication mechanism that is configured for the domain.

You can also manage the admin console login authentication URL and the single sign on web client login settings from this page.

#### Setting Admin Console Redirect URL

This sets up the login and logout URL to redirect admins to with their auth token has expired.  

1.  Type the login redirect URL. For example, https://example.com

2.  Type the logout redirect URL.

3.  Click <span class="attribute">Save</span>.

#### Setting the Single Sign On Web Client Redirect URLs and Allowed User Agents

When EMCS is configured for single sign-on authentication to the EhloMail Web Client, the server is configured to redirect users to a specific URL. You can configure the web client sign in and sign out URL and the UAs allowed for the sign in URL on the domain.

1.  In the <span class="attribute">Web client login redirect URL tex</span>t box, type the URL to redirect users to when the auth token is expired.

2.  In the <span class="attribute">Web client logout redirect URL</span> text box, type the URL to redirect users to when they click Sign out.

3.  In the <span class="attribute">Allowed user agent when login</span> text box, type the supported platforms and browsers that are allowed. If you do not set this, all user agents (UA) are allowed. Click <span class="attribute">Add</span> to add more than type.

4.  In the <span class="attribute">Allowed user agent when logout text</span> box, type the sign out URL and UAs allowed to redirect users to when they sign out. Click <span class="attribute">Add</span> to add more than one type

5.  In <span class="attribute">Allowed IP when login t</span>ext box, type the IP addresses that are allowed as the sign out URL.

6.  In <span class="attribute">Allowed IP when logout</span> text box, type the IP addresses that are allowed as the sign out URL.

7.  Click <span class="attribute">Save</span>.

Example of how to enter text to describe the user agent if you wanted to limit access to only Firefox, Internet Explorer, Chrome, and Safari on computers running Windows, and Safari on Apple Mac Computers. Enter each in a separate text box.

.*Windows.*Firefox/3

.*MSIE.*Windows.*

.*Windows.*Chrome.*

.*Windows.*Safari.*

.*Macintosh.*Safari.*
