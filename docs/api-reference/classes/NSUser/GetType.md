---
uid: crmscript_ref_NSUser_GetType
title: Integer GetType()
intellisense: NSUser.GetType
keywords: NSUser, GetType
so.topic: reference
---

# Integer GetType()

NSUser type: 1=InternalAssociate, 2=ResourceAssociate, 3=ExternalAssociate, 4=AnonymousAssociate, 5=SystemAssociate

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
NSUser thing;
Integer type  = thing.GetType();
```
