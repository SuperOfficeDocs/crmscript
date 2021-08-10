---
uid: crmscript_ref_NSAssociate_GetType
title: Integer GetType()
intellisense: NSAssociate.GetType
keywords: NSAssociate, GetType
so.topic: reference
---

# Integer GetType()

User type - 1 = internal user, 2 = resource, 3 = external user, 4 = anonymous, 5 = system

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = InternalAssociate 
     - Enum: 2 = ResourceAssociate 
     - Enum: 3 = ExternalAssociate 
     - Enum: 4 = AnonymousAssociate 
     - Enum: 5 = SystemAssociate 

```crmscript
NSAssociate thing;
Integer type  = thing.GetType();
```

