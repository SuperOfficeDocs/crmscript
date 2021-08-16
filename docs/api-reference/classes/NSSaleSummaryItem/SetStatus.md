---
uid: crmscript_ref_NSSaleSummaryItem_SetStatus
title: SetStatus(Integer status)
intellisense: NSSaleSummaryItem.SetStatus
keywords: NSSaleSummaryItem, GetStatus
so.topic: reference
---

# SetStatus(Integer status)

The sale's status, indicating whether the sale is open(1), sold(2) or lost(3).

**Parameter:** 
 - **status** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = Open 
     - Enum: 2 = Sold 
     - Enum: 3 = Lost 
     - Enum: 4 = Stalled 
     - Enum: 1000 = SaintAll 

```crmscript
NSSaleSummaryItem thing;
Integer status;
thing.SetStatus(status);
```

