---
uid: crmscript_ref_NSModuleLicense_GetAllowedUserType
title: Integer GetAllowedUserType()
intellisense: NSModuleLicense.GetAllowedUserType
keywords: NSModuleLicense, GetAllowedUserType
so.topic: reference
---

# Integer GetAllowedUserType()

Allowed associate type for user licenses: internal(0), external(4).

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
NSModuleLicense thing;
Integer allowedUserType  = thing.GetAllowedUserType();
```
