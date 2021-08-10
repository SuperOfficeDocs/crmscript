---
uid: crmscript_ref_NSUserAgent_ChangePassword
title: Bool ChangePassword(Integer associateId, String oldPassword, String newPassword)
intellisense: NSUserAgent.ChangePassword
keywords: NSUserAgent, ChangePassword
so.topic: reference
---

# Bool ChangePassword(Integer associateId, String oldPassword, String newPassword)

Change password for a user.

**Parameters:**
 - **associateId** AssociateId of the user to change password for.
 - **oldPassword** The current password of the user.  Administrators can leave this blank to force a new password upon a user.
 - **newPassword** The new password for the user

**Returns:** Bool

```crmscript
NSUserAgent agent;
Integer associateId;
String oldPassword;
String newPassword;
Bool res = agent.ChangePassword(associateId, oldPassword, newPassword);
```

