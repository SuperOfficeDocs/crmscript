---
uid: crmscript_ref_NSActivitySummary_SetNumFreeActivities
title: SetNumFreeActivities(Integer numFreeActivities)
intellisense: NSActivitySummary.SetNumFreeActivities
keywords: NSActivitySummary, GetNumFreeActivities
so.topic: reference
---

# SetNumFreeActivities(Integer numFreeActivities)

Number of activities of the type 'free'. Sales and documents are not activities in this case, only diary appointments and tasks.

## Parameters

* **numFreeActivities** Integer

```crmscript
NSActivitySummary thing;
Integer numFreeActivities;
thing.SetNumFreeActivities(numFreeActivities);
```

