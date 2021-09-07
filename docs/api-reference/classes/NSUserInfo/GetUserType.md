---
uid: crmscript_ref_NSUserInfo_GetUserType
title: Integer GetUserType()
intellisense: NSUserInfo.GetUserType
keywords: NSUserInfo, GetUserType
so.topic: reference
---

# Integer GetUserType()

**Returns:** Integer

## Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUserInfo thing;
Integer userType  = thing.GetUserType();
```
