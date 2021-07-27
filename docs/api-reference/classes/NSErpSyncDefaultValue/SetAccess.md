﻿---
uid: crmscript_ref_NSErpSyncDefaultValue_SetAccess
title: SetAccess(NSFieldAccess access)
intellisense: NSErpSyncDefaultValue.SetAccess
keywords: NSErpSyncDefaultValue, GetAccess
so.topic: reference
---

Access restrictions for the field

**Parameter:** 
 - **access** NSFieldAccess
     - Enum: 0 = Normal 
     - Enum: 1 = Mandatory 
     - Enum: 2 = ReadOnly 

```crmscript
NSErpSyncDefaultValue thing;
NSFieldAccess access;
thing.SetAccess(access);
```

