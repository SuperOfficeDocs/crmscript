---
uid: crmscript_ref_NSAppointmentEntity_SetCautionWarning
title: SetCautionWarning(NSAppointmentCautionWarning cautionWarning)
intellisense: NSAppointmentEntity.SetCautionWarning
keywords: NSAppointmentEntity, GetCautionWarning
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
NSAppointmentEntity thing;
NSAppointmentCautionWarning cautionWarning;
thing.SetCautionWarning(cautionWarning);
```
