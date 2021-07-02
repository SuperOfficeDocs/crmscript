﻿---
uid: crmscript_ref_NSErpConnectionData_GetErpActorTypes
title: ErpActorType[] GetErpActorTypes()
intellisense: NSErpConnectionData.GetErpActorTypes
keywords: NSErpConnectionData, GetErpActorTypes
so.topic: reference
---

Contains all mapped ErpActorType for this CrmActorType

**Returns:** ErpActorType[]

     - Enum: 0 = Unknown 
     - Enum: 1 = Customer 
     - Enum: 2 = Supplier 
     - Enum: 3 = Partner 
     - Enum: 4 = Person 
     - Enum: 5 = Project 
     - Enum: 6 = Employee 
     - Enum: 7 = Sale 

```crmscript
NSErpConnectionData thing;
ErpActorType[] erpActorTypes  = thing.GetErpActorTypes();
```


