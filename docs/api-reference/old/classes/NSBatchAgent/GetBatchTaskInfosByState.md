---
uid: crmscript_ref_NSBatchAgent_GetBatchTaskInfosByState
title: NSBatchTaskInfo[] GetBatchTaskInfosByState(Integer state)
intellisense: NSBatchAgent.GetBatchTaskInfosByState
keywords: NSBatchAgent, GetBatchTaskInfosByState
so.topic: reference
---

# NSBatchTaskInfo[] GetBatchTaskInfosByState(Integer state)

Gets an array of NSBatchTaskInfo with state defined by a BatchTaskState.

## Parameters

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
Integer state;
NSBatchTaskInfo[] res = agent.GetBatchTaskInfosByState(state);
```
