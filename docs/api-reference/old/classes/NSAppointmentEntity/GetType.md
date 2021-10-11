---
uid: crmscript_ref_NSAppointmentEntity_GetType
title: Integer GetType()
intellisense: NSAppointmentEntity.GetType
keywords: NSAppointmentEntity, GetType
so.topic: reference
---

# Integer GetType()

The different types of appointment, if the appointment is supposed to be shown in the diary or checklist, or if it's a document. See the different types of appointments in the database manual.

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
NSAppointmentEntity thing;
Integer type  = thing.GetType();
```