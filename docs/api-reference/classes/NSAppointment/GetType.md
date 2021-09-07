---
uid: crmscript_ref_NSAppointment_GetType
title: Integer GetType()
intellisense: NSAppointment.GetType
keywords: NSAppointment, GetType
so.topic: reference
---

# Integer GetType()

The different types of appointment, if the appointment is supposed to be shown in the diary or checklist, or if it's a document. See the different types of appointments in the database manual.

**Returns:** Integer

## Enum: appointment type

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
NSAppointment thing;
Integer type  = thing.GetType();
```
