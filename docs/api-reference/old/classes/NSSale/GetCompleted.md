---
uid: crmscript_ref_NSSale_GetCompleted
title: Integer GetCompleted()
intellisense: NSSale.GetCompleted
keywords: NSSale, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

The Sale completed state. The completed state is either Started or Completed. NotStarted is treated as Started. The value maps to the Done database field.

**Returns:** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSSale thing;
Integer completed  = thing.GetCompleted();
```
