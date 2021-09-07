---
uid: crmscript_ref_NSUserAgent_ChangeUserType
title: NSUser ChangeUserType(NSUser user, Integer userType)
intellisense: NSUserAgent.ChangeUserType
keywords: NSUserAgent, ChangeUserType
so.topic: reference
---

# NSUser ChangeUserType(NSUser user, Integer userType)

Get a user from the user name.

**Returns:** NSUser

## Parameters

| Parameter | Type | Description |
|---|---|---|
| user | NSUser | User name of the user to get. |
| userType | Integer | |

### userType

## Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserAgent agent;
NSUser user;
Integer userType;
NSUser res = agent.ChangeUserType(user, userType);
```
