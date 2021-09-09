---
uid: crmscript_ref_NSBatchAgent_GetBatchTaskInfosByAssociatesAndState
title: NSBatchTaskInfo[] GetBatchTaskInfosByAssociatesAndState(Integer[] associateIds, Integer state)
intellisense: NSBatchAgent.GetBatchTaskInfosByAssociatesAndState
keywords: NSBatchAgent, GetBatchTaskInfosByAssociatesAndState
so.topic: reference
---

# NSBatchTaskInfo[] GetBatchTaskInfosByAssociatesAndState(Integer[] associateIds, Integer state)

Get an array of NSBatchTaskInfo for the provided associate id's and batch task state.

## Parameters

* **associateIds** Array of associate id's.
* **state** The BatchTaskState to get batch tasks for.

**Returns:** NSBatchTaskInfo[]

### Enum: BatchTaskState

* 0 = Unknown
* 1 = New
* 2 = Aquired
* 3 = Started
* 4 = Succeeded
* 5 = Failed
* 6 = SucceededManualCleanup
* 99999 = All

## Example

```crmscript
NSBatchAgent agent;
Integer[] associateIds;
Integer state;
NSBatchTaskInfo[] res = agent.GetBatchTaskInfosByAssociatesAndState(associateIds, state);
```
