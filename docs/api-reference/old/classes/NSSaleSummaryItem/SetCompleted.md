---
uid: crmscript_ref_NSSaleSummaryItem_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSSaleSummaryItem.SetCompleted
keywords: NSSaleSummaryItem, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Completed state. NotStarted(1) or Completed(3)

## Parameters

* **completed** Integer

## Completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSSaleSummaryItem thing;
Integer completed;
thing.SetCompleted(completed);
```
