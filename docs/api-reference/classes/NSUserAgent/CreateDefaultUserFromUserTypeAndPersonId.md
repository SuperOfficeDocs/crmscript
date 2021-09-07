---
uid: crmscript_ref_NSUserAgent_CreateDefaultUserFromUserTypeAndPersonId
title: NSUser CreateDefaultUserFromUserTypeAndPersonId(Integer userType, Integer personId)
intellisense: NSUserAgent.CreateDefaultUserFromUserTypeAndPersonId
keywords: NSUserAgent, CreateDefaultUserFromUserTypeAndPersonId
so.topic: reference
---

# NSUser CreateDefaultUserFromUserTypeAndPersonId(Integer userType, Integer personId)

Create default NSUser providing the associate type and person id.  System and Anonymous users can be created without an exsisting person and permits person id to be 0.

## Parameters

* **userType** Type of associate for the user
* **personId** Primary key of the person to become a user.

**Returns:** NSUser

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserAgent agent;
Integer userType;
Integer personId;
NSUser res = agent.CreateDefaultUserFromUserTypeAndPersonId(userType, personId);
```
