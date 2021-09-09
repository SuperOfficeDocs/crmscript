---
uid: crmscript_ref_NSSaleEntity_GetCompleted
title: Integer GetCompleted()
intellisense: NSSaleEntity.GetCompleted
keywords: NSSaleEntity, GetCompleted
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
NSSaleEntity thing;
Integer completed  = thing.GetCompleted();
```
