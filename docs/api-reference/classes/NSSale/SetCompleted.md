---
uid: crmscript_ref_NSSale_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSSale.SetCompleted
keywords: NSSale, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Sale completed state. The completed state is either Started or Completed. NotStarted is treated as Started. The value maps to the Done database field.

## Parameters

* **completed** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSSale thing;
Integer completed;
thing.SetCompleted(completed);
```
