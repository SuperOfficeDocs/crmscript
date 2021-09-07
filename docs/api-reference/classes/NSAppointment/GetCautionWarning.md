---
uid: crmscript_ref_NSAppointment_GetCautionWarning
title: NSAppointmentCautionWarning GetCautionWarning()
intellisense: NSAppointment.GetCautionWarning
keywords: NSAppointment, GetCautionWarning
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
NSAppointment thing;
NSAppointmentCautionWarning cautionWarning  = thing.GetCautionWarning();
```
