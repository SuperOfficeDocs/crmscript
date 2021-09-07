---
uid: crmscript_ref_NSActivitySummaryItem_GetCompleted
title: Integer GetCompleted()
intellisense: NSActivitySummaryItem.GetCompleted
keywords: NSActivitySummaryItem, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

The Completed state. NotStarted(1) or Completed(3)

**Returns:** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSActivitySummaryItem thing;
Integer completed  = thing.GetCompleted();
```
