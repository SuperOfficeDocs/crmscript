---
uid: crmscript_ref_NSPersonAgent_GetColleaguesBySource
title: NSPerson[] GetColleaguesBySource(Integer sourceType, Integer count)
intellisense: NSPersonAgent.GetColleaguesBySource
keywords: NSPersonAgent, GetColleaguesBySource
so.topic: reference
---

# NSPerson[] GetColleaguesBySource(Integer sourceType, Integer count)

Gets the persons working in the same company as the logged-on user. The list of persons could be retrieved from the history list, the diary view list, or from all sources.

**Returns:** NSPerson[]

## Parameters

| Parameter | Type | Description |
|---|---|---|
| sourceType | Integer | The source the colleagues should be retrieved from. <see cref="AssociateSourceType"/> for more information. |
| count | Integer | |

### sourceType

* Enum: 0 = Unknown
* Enum: 1 = NSHistory
* Enum: 2 = DiaryViewList
* Enum: 4 = Department
* Enum: 7 = All

## Example

```crmscript
NSPersonAgent agent;
Integer sourceType;
Integer count;
NSPerson[] res = agent.GetColleaguesBySource(sourceType, count);
```