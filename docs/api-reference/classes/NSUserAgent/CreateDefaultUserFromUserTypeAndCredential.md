---
uid: crmscript_ref_NSUserAgent_CreateDefaultUserFromUserTypeAndCredential
title: NSUser CreateDefaultUserFromUserTypeAndCredential(Integer userType, Integer contactId, String credentialType, String credentialValue, String credentialDisplayValue)
intellisense: NSUserAgent.CreateDefaultUserFromUserTypeAndCredential
keywords: NSUserAgent, CreateDefaultUserFromUserTypeAndCredential
so.topic: reference
---

# NSUser CreateDefaultUserFromUserTypeAndCredential(Integer userType, Integer contactId, String credentialType, String credentialValue, String credentialDisplayValue)

Creates an NSPersonEntity with default values based on the contactId and credentials.

## Parameters

* **userType** Type of associate for the user
* **contactId** Contact id of the person
* **credentialType** Type of credentials, corresponding to name of plugin and type in the credentials table.
* **credentialValue** This is the actuall value of the credentials.  This will typically be the password or teh users SID in active directory
* **credentialDisplayValue** The value displayed to the user. this will typically be the users login name in active directory.

**Returns:** NSUser

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate
