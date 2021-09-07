---
uid: crmscript_ref_NSAppointment_GetPrivate
title: AppointmentPrivate GetPrivate()
intellisense: NSAppointment.GetPrivate
keywords: NSAppointment, GetPrivate
so.topic: reference
---

# AppointmentPrivate GetPrivate()

Obsolete, but still maintained field for appointment privacy; denormalization of visiblefor status

**Returns:** AppointmentPrivate

## Enum: AppointmentPrivate

* 0 = Public
* 1 = PrivateUser
* 2 = PrivateGroup

## Example

```crmscript
NSAppointment thing;
AppointmentPrivate private  = thing.GetPrivate();
```
