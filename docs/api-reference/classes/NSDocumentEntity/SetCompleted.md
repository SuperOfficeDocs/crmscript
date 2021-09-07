---
uid: crmscript_ref_NSDocumentEntity_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSDocumentEntity.SetCompleted
keywords: NSDocumentEntity, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

Document Completed state. This is the part of the Status property.

## Parameters

* **completed** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSDocumentEntity thing;
Integer completed;
thing.SetCompleted(completed);
```
