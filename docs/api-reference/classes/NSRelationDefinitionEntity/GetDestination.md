---
uid: crmscript_ref_NSRelationDefinitionEntity_GetDestination
title: Integer GetDestination()
intellisense: NSRelationDefinitionEntity.GetDestination
keywords: NSRelationDefinitionEntity, GetDestination
so.topic: reference
---

# Integer GetDestination()

The destination of the relation

**Returns:** Integer

     - Enum: 0 = None 
     - Enum: 1 = Contact 
     - Enum: 2 = Person 
     - Enum: 3 = Both 

```crmscript
NSRelationDefinitionEntity thing;
Integer destination  = thing.GetDestination();
```

