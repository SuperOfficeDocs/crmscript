---
uid: crmscript_ref_NSAlarmData_GetAppointmentType
title: Integer GetAppointmentType()
intellisense: NSAlarmData.GetAppointmentType
keywords: NSAlarmData, GetAppointmentType
so.topic: reference
---

# Integer GetAppointmentType()

where=no start time,note,docin, docout

**Returns:** Integer

## Enum: address type

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
NSAlarmData thing;
Integer appointmentType  = thing.GetAppointmentType();
```
