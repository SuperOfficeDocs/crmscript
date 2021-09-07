---
uid: crmscript_ref_NSBatchTaskInfo_GetState
title: Integer GetState()
intellisense: NSBatchTaskInfo.GetState
keywords: NSBatchTaskInfo, GetState
so.topic: reference
---

# Integer GetState()

BatchTaskState of the task.

**Returns:** Integer

## Enum: BatchTaskState

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
Integer state  = thing.GetState();
```
