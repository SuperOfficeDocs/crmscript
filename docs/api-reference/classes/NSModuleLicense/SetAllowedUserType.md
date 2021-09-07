---
uid: crmscript_ref_NSModuleLicense_SetAllowedUserType
title: SetAllowedUserType(Integer allowedUserType)
intellisense: NSModuleLicense.SetAllowedUserType
keywords: NSModuleLicense, GetAllowedUserType
so.topic: reference
---

# SetAllowedUserType(Integer allowedUserType)

Allowed associate type for user licenses: internal(0), external(4).

## Parameters

* **allowedUserType** Integer

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSModuleLicense thing;
Integer allowedUserType;
thing.SetAllowedUserType(allowedUserType);
```
