---
uid: crmscript_ref_NSDocumentEntity_GetCompleted
title: Integer GetCompleted()
intellisense: NSDocumentEntity.GetCompleted
keywords: NSDocumentEntity, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

Document Completed state. This is the part of the Status property.

**Returns:** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSDocumentEntity thing;
Integer completed  = thing.GetCompleted();
```
