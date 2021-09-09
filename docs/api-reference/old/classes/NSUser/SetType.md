---
uid: crmscript_ref_NSUser_SetType
title: SetType(Integer type)
intellisense: NSUser.SetType
keywords: NSUser, GetType
so.topic: reference
---

# SetType(Integer type)

NSUser type: 1=InternalAssociate, 2=ResourceAssociate, 3=ExternalAssociate, 4=AnonymousAssociate, 5=SystemAssociate

## Parameters

* **type** Integer

### Enum: associateType

* 0 = Unknown
* 1 = InternalAssociate
* 2 = ResourceAssociate
* 3 = ExternalAssociate
* 4 = AnonymousAssociate
* 5 = SystemAssociate

## Example

```crmscript
NSUser thing;
Integer type;
thing.SetType(type);
```
