---
uid: crmscript_ref_NSPersonAgent_GetOwnerOnPersonId
title: NSPerson GetOwnerOnPersonId(Integer personId)
intellisense: NSPersonAgent.GetOwnerOnPersonId
keywords: NSPersonAgent, GetOwnerOnPersonId
so.topic: reference
---

# NSPerson GetOwnerOnPersonId(Integer personId)

Get the owner of the person by id.

**Returns:** NSPerson

## Parameters

| Parameter | Type | Description |
|---|---|---|
| personId | Integer | |

## Example

```crmscript
NSPersonAgent agent;
Integer personId;
NSPerson res = agent.GetOwnerOnPersonId(personId);
```
