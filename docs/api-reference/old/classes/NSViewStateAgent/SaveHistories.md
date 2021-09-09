---
uid: crmscript_ref_NSViewStateAgent_SaveHistories
title: NSHistory[] SaveHistories(String historyName, NSHistory[] history)
intellisense: NSViewStateAgent.SaveHistories
keywords: NSViewStateAgent, SaveHistories
so.topic: reference
---

# NSHistory[] SaveHistories(String historyName, NSHistory[] history)

Replaces the existing history-list for the currently logged-in user. All elements must belong to the same history list. If not they are ignored.

**Returns:** NSHistory[]

## Parameters

| Parameter | Type | Description |
|---|---|---|
| historyName | String | |
| history | NSHistory[] | Array of new history items to save. |

## Example

```crmscript
NSViewStateAgent agent;
String historyName;
NSHistory[] history;
NSHistory[] res = agent.SaveHistories(historyName, history);
```
