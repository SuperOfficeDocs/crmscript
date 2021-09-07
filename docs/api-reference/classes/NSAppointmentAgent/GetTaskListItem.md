---
uid: crmscript_ref_NSAppointmentAgent_GetTaskListItem
title: NSTaskListItem GetTaskListItem(Integer taskListItemId);
intellisense: NSAppointmentAgent.GetTaskListItem
keywords: NSAppointmentAgent, GetTaskListItem
so.topic: reference
---

# NSTaskListItem GetTaskListItem(Integer taskListItemId);

Gets an NSTaskListItem object.

## Parameters

* **taskListItemId** The identifier of the NSTaskListItem object

**Returns:** NSTaskListItem

```crmscript
NSAppointmentAgent agent;
NSTaskListItem thing = agent.GetTaskListItem(123);
```

