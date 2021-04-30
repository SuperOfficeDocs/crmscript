﻿---
uid: crmscript_ref_NSTicketPriorityEntity_GetFlags
title: TicketPriorityFlags GetFlags()
intellisense: NSTicketPriorityEntity.GetFlags
keywords: NSTicketPriorityEntity, GetFlags
so.topic: reference
---

A bitmask of flags.

**Returns:** TicketPriorityFlags

     - Enum: 0 = Unknown 
     - Enum: 1 = External 
     - Enum: 2 = Default 
     - Enum: 4 = AlertSchedule 

```crmscript
NSTicketPriorityEntity thing;
TicketPriorityFlags flags  = thing.GetFlags();
```

