---
uid: crmscript_ref_NSActivitySummaryItem_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSActivitySummaryItem.SetCompleted
keywords: NSActivitySummaryItem, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Completed state. NotStarted(1) or Completed(3)

## Parameter

| Parameter | Type | Description |
|---|---|---|
| completed | Integer | |

### Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSActivitySummaryItem thing;
Integer completed;
thing.SetCompleted(completed);
```
