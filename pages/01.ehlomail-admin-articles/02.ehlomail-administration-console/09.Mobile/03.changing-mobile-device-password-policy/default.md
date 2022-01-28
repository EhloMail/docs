---
title: 'Changing mobile device password policy'
visible: true
---

Once a mobile device is locked by the server password policy, to remove the PIN requirement on the device, the device sync relationship with the server must be deleted and then the PIN requirement for the device must be turned off. After the PIN requirement is turned off, the user re syncs the device to the EhloMail account.

1.  Open the user account to be modified.

2.  Open the <span style="font-weight: bold;">Zimbra Network > Mobile</span> tab and uncheck <span style="font-weight: bold;">Force pin on device.</span>

3.  Once the password policy has been turned off, notify users to resync their device to their EhloMail account as follows:

• If the device is a WM6 device, the user syncs to the account. After the sync has completed, instruct the user to go to the Lock setting on the device and turn off the device PIN.

• If the device is an iPhone/iPod Touch 3.0 or above, the user syncs to the account. After the sync, instruct the user to go to the Settings > General properties and turn off Passcode Lock.

• If the iPhone/iPod Touch is prior to 3.0, an Apple software bug that prevents downloading new device policies to take effect. The user must delete the EhloMail account from the iPhone/iPod Touch, turn the PIN off, and then resetup sync with their account. Because the password requirement was turned off, a PIN is not asked for.