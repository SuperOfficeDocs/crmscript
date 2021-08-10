---
uid: crmscript_ref_NSSaleEntity_GetReopenDate
title: DateTime GetReopenDate()
intellisense: NSSaleEntity.GetReopenDate
keywords: NSSaleEntity, GetReopenDate
so.topic: reference
---

# DateTime GetReopenDate()

Date the sale is to be reopened; valid only for status=stalled. Not necessarily the same as the nextDueDate.

**Returns:** DateTime

```crmscript
NSSaleEntity thing;
DateTime reopenDate  = thing.GetReopenDate();
```

