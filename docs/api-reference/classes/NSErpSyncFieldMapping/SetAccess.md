﻿---
uid: crmscript_ref_NSErpSyncFieldMapping_SetAccess
title: SetAccess(FieldAccess access)
intellisense: NSErpSyncFieldMapping.SetAccess
keywords: NSErpSyncFieldMapping, GetAccess
so.topic: reference
---

Access restrictions for the field

**Parameter:** 
 - **access** FieldAccess
     - Enum: 0 = Normal 
     - Enum: 1 = Mandatory 
     - Enum: 2 = ReadOnly 

```crmscript
NSErpSyncFieldMapping thing;
FieldAccess access;
thing.SetAccess(access);
```
