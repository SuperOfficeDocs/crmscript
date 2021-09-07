---
uid: crmscript_ref_NSAssociate_GetType
title: Integer GetType()
intellisense: NSAssociate.GetType
keywords: NSAssociate, GetType
so.topic: reference
---

# Integer GetType()

User type* 1 = internal user, 2 = resource, 3 = external user, 4 = anonymous, 5 = system

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
NSAssociate thing;
Integer type  = thing.GetType();
```
