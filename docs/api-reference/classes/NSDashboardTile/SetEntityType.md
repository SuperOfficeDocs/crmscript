---
uid: crmscript_ref_NSDashboardTile_SetEntityType
title: SetEntityType(Integer entityType)
intellisense: NSDashboardTile.SetEntityType
keywords: NSDashboardTile, GetEntityType
so.topic: reference
---

# SetEntityType(Integer entityType)

The tile entity type

**Parameter:** 
 - **entityType** Integer
     - Enum: 0 = None 
     - Enum: 1 = Company 
     - Enum: 2 = Project 
     - Enum: 3 = Sale 
     - Enum: 4 = Product 
     - Enum: 5 = Activity 
     - Enum: 6 = Document 
     - Enum: 7 = WebPanel 
     - Enum: 8 = Followup 

```crmscript
NSDashboardTile thing;
Integer entityType;
thing.SetEntityType(entityType);
```

