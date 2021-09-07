---
uid: crmscript_ref_NSAppointment_SetCautionWarning
title: SetCautionWarning(NSAppointmentCautionWarning cautionWarning)
intellisense: NSAppointment.SetCautionWarning
keywords: NSAppointment, GetCautionWarning
so.topic: reference
---

# SetCautionWarning(NSAppointmentCautionWarning cautionWarning)

Status field to indicate appointments that have some sort of problem

## Parameters

* **cautionWarning** NSAppointmentCautionWarning

### Enum: CautionWarning

* 0 = OK
* 1 = NotInSync
* 2 = NotNotifiedByEmail
* 3 = RecurrencePatternNotSupported
* 4 = IncomingRecurrenceChangeNotSupported
* 5 = ExternalParticipantsDateTimeMismatch

## Example

```crmscript
NSAppointment thing;
NSAppointmentCautionWarning cautionWarning;
thing.SetCautionWarning(cautionWarning);
```
