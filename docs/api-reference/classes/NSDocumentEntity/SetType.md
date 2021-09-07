---
uid: crmscript_ref_NSDocumentEntity_SetType
title: SetType(Integer type)
intellisense: NSDocumentEntity.SetType
keywords: NSDocumentEntity, GetType
so.topic: reference
---

# SetType(Integer type)

Is this a normal document or a mail-merge or report?

## Parameters

* **type** Integer

### Enum: appointment type

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
Integer type;
thing.SetType(type);
```
