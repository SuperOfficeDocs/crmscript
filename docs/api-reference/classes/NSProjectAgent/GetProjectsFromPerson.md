---
uid: crmscript_ref_NSProjectAgent_GetProjectsFromPerson
title: NSProject[] GetProjectsFromPerson(Integer personId)
intellisense: NSProjectAgent.GetProjectsFromPerson
keywords: NSProjectAgent, GetProjectsFromPerson
so.topic: reference
---

Return all projects where the person is project member.

**Parameters:**
 - **personId** The person id

**Returns:** ProjectListEntity

```crmscript
NSProjectAgent agent;
Integer personId;
NSProject[] res = agent.GetProjectsFromPerson(personId);
```

