---
uid: crmscript_ref_NSUserInfo_SetUserType
title: SetUserType(Integer userType)
intellisense: NSUserInfo.SetUserType
keywords: NSUserInfo, GetUserType
so.topic: reference
---

# SetUserType(Integer userType)

## Parameters

* **userType** Integer

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserInfo thing;
Integer userType;
thing.SetUserType(userType);
```
