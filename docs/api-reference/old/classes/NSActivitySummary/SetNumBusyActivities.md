---
uid: crmscript_ref_NSActivitySummary_SetNumBusyActivities
title: SetNumBusyActivities(Integer numBusyActivities)
intellisense: NSActivitySummary.SetNumBusyActivities
keywords: NSActivitySummary, GetNumBusyActivities
so.topic: reference
---

# SetNumBusyActivities(Integer numBusyActivities)

Number of activities and tasks in the diary that are of type 'busy'. Sales and documents are not activities in this case, only diary appointments and tasks.

## Parameters

* **numBusyActivities** Integer

```crmscript
NSActivitySummary thing;
Integer numBusyActivities;
thing.SetNumBusyActivities(numBusyActivities);
```

