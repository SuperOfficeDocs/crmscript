---
uid: crmscript_ref_NSActivitySummaryItem_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSActivitySummaryItem.SetCompleted
keywords: NSActivitySummaryItem, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Completed state. NotStarted(1) or Completed(3)

**Parameter:** 
 - **completed** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = NotStarted 
     - Enum: 2 = Started 
     - Enum: 3 = Completed 

```crmscript
NSActivitySummaryItem thing;
Integer completed;
thing.SetCompleted(completed);
```

