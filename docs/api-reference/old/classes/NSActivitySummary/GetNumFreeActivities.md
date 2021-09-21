---
uid: crmscript_ref_NSActivitySummary_GetNumFreeActivities
title: Integer GetNumFreeActivities()
intellisense: NSActivitySummary.GetNumFreeActivities
keywords: NSActivitySummary, GetNumFreeActivities
so.topic: reference
---

# Integer GetNumFreeActivities()

Number of activities of the type 'free'. Sales and documents are not activities in this case, only diary appointments and tasks.

**Returns:** Integer

```crmscript
NSActivitySummary thing;
Integer numFreeActivities  = thing.GetNumFreeActivities();
```

