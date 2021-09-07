---
uid: crmscript_ref_NSMailMergeTask_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSMailMergeTask.SetCompleted
keywords: NSMailMergeTask, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

Completed status for task

## Parameters

* **completed** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSMailMergeTask thing;
Integer completed;
thing.SetCompleted(completed);
```
