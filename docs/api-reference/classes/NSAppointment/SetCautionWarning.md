﻿---
uid: crmscript_ref_NSAppointment_SetCautionWarning
title: SetCautionWarning(NSAppointmentCautionWarning cautionWarning)
intellisense: NSAppointment.SetCautionWarning
keywords: NSAppointment, GetCautionWarning
so.topic: reference
---

Status field to indicate appointments that have some sort of problem

**Parameter:** 
 - **cautionWarning** NSAppointmentCautionWarning
     - Enum: 0 = OK 
     - Enum: 1 = NotInSync 
     - Enum: 2 = NotNotifiedByEmail 
     - Enum: 3 = RecurrencePatternNotSupported 
     - Enum: 4 = IncomingRecurrenceChangeNotSupported 
     - Enum: 5 = ExternalParticipantsDateTimeMismatch 

```crmscript
NSAppointment thing;
NSAppointmentCautionWarning cautionWarning;
thing.SetCautionWarning(cautionWarning);
```

