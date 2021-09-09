---
uid: crmscript_ref_NSAppointmentEntity_GetCautionWarning
title: NSAppointmentCautionWarning GetCautionWarning()
intellisense: NSAppointmentEntity.GetCautionWarning
keywords: NSAppointmentEntity, GetCautionWarning
so.topic: reference
---

# NSAppointmentCautionWarning GetCautionWarning()

Status field to indicate appointments that have some sort of problem

**Returns:** NSAppointmentCautionWarning

## Enum: CautionWarning

* 0 = OK
* 1 = NotInSync
* 2 = NotNotifiedByEmail
* 3 = RecurrencePatternNotSupported
* 4 = IncomingRecurrenceChangeNotSupported
* 5 = ExternalParticipantsDateTimeMismatch

## Example

```crmscript
NSAppointmentEntity thing;
NSAppointmentCautionWarning cautionWarning  = thing.GetCautionWarning();
```
