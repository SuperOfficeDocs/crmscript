---
uid: crmscript_ref_NSBatchAgent_GetBatchTaskInfosByNameAndState
title: NSBatchTaskInfo[] GetBatchTaskInfosByNameAndState(String name, Integer state)
intellisense: NSBatchAgent.GetBatchTaskInfosByNameAndState
keywords: NSBatchAgent, GetBatchTaskInfosByNameAndState
so.topic: reference
---

# NSBatchTaskInfo[] GetBatchTaskInfosByNameAndState(String name, Integer state)

Gets an array of NSBatchTaskInfo with state defined by a BatchTaskState and the batchtask definition name.

## Parameters

* **name** Batchtask definition name.
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
String name;
Integer state;
NSBatchTaskInfo[] res = agent.GetBatchTaskInfosByNameAndState(name, state);
```
