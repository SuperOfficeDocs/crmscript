---
uid: crmscript_ref_NSSale_SetNextDueDate
title: SetNextDueDate(DateTime nextDueDate)
intellisense: NSSale.SetNextDueDate
keywords: NSSale, GetNextDueDate
so.topic: reference
---

# SetNextDueDate(DateTime nextDueDate)

Next due date, this is a denormalization of 'closest future activity date, or most recent if no future activities'. Maintained by the system, but very convenient for searching.

**Parameter:** 
 - **nextDueDate** DateTime

```crmscript
NSSale thing;
DateTime nextDueDate;
thing.SetNextDueDate(nextDueDate);
```

