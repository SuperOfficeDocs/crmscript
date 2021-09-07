---
uid: crmscript_ref_NSAlarmData_SetAppointmentType
title: SetAppointmentType(Integer appointmentType)
intellisense: NSAlarmData.SetAppointmentType
keywords: NSAlarmData, GetAppointmentType
so.topic: reference
---

# SetAppointmentType(Integer appointmentType)

where=no start time,note,docin, docout

## Parameters

* **appointmentType** Integer

### Enum: appointmentType

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
Integer appointmentType;
thing.SetAppointmentType(appointmentType);
```
