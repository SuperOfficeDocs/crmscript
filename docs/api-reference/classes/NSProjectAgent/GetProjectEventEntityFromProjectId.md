---
uid: crmscript_ref_NSProjectAgent_GetProjectEventEntityFromProjectId
title: NSProjectEventEntity GetProjectEventEntityFromProjectId(Integer projectId)
intellisense: NSProjectAgent.GetProjectEventEntityFromProjectId
keywords: NSProjectAgent, GetProjectEventEntityFromProjectId
so.topic: reference
---

# NSProjectEventEntity GetProjectEventEntityFromProjectId(Integer projectId)

Get an NSProjectEventEntity based on a projectId.

## Parameters

* **projectId** The projectId to get an NSProjectEventEntity for

**Returns:** NSProjectEventEntity

```crmscript
NSProjectAgent agent;
Integer projectId;
NSProjectEventEntity res = agent.GetProjectEventEntityFromProjectId(projectId);
```

