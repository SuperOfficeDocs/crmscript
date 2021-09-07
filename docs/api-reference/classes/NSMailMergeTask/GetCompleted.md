---
uid: crmscript_ref_NSMailMergeTask_GetCompleted
title: Integer GetCompleted()
intellisense: NSMailMergeTask.GetCompleted
keywords: NSMailMergeTask, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

Completed status for task.

**Returns:** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSMailMergeTask thing;
Integer completed  = thing.GetCompleted();
```
