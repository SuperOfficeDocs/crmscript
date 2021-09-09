---
uid: crmscript_ref_NSBatchTaskInfo_SetState
title: SetState(Integer state)
intellisense: NSBatchTaskInfo.SetState
keywords: NSBatchTaskInfo, GetState
so.topic: reference
---

# SetState(Integer state)

BatchTaskState of the task.

## Parameters

* **state** Integer

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
NSBatchTaskInfo thing;
Integer state;
thing.SetState(state);
```
