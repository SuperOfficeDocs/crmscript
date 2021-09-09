---
uid: crmscript_ref_NSProjectAgent_GetProjectMembersById
title: NSProjectMember[] GetProjectMembersById(Integer[] projectMemberIds)
intellisense: NSProjectAgent.GetProjectMembersById
keywords: NSProjectAgent, GetProjectMembersById
so.topic: reference
---

# NSProjectMember[] GetProjectMembersById(Integer[] projectMemberIds)

Returns an array of project members

**Returns:** NSProjectMember[]

## Parameters

| Parameter | Type | Description |
|---|---|---|
| projectMemberIds | Integer[] | |

## Example

```crmscript
NSProjectAgent agent;
Integer rojectMemberIds;
NSProjectMember[] res = agent.GetProjectMembersById(projectMemberIds);
```
