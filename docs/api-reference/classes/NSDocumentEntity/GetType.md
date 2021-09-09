---
uid: crmscript_ref_NSDocumentEntity_GetType
title: Integer GetType()
intellisense: NSDocumentEntity.GetType
keywords: NSDocumentEntity, GetType
so.topic: reference
---

# Integer GetType()

Is this a normal document or a mail-merge or report?

**Returns:** Integer

## Enum: appointmentType

* 0 = Unknown
* 1 = inDiary
* 2 = inChecklist
* 3 = Note
* 4 = Document
* 5 = SavedReport
* 6 = BookingForDiary
* 7 = BookingForChecklist
* 8 = MergeDraft
* 9 = MergeFinal

## Example

```crmscript
NSDocumentEntity thing;
Integer type  = thing.GetType();
```
