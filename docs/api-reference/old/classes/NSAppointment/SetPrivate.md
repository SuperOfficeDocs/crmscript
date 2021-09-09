---
uid: crmscript_ref_NSAppointment_SetPrivate
title: SetPrivate(AppointmentPrivate private)
intellisense: NSAppointment.SetPrivate
keywords: NSAppointment, GetPrivate
so.topic: reference
---

# SetPrivate(AppointmentPrivate private)

Obsolete, but still maintained field for appointment privacy; denormalization of visiblefor status

## Parameters

* **private** AppointmentPrivate

### Enum: AppointmentPrivate

* 0 = Public
* 1 = PrivateUser
* 2 = PrivateGroup

## Example

```crmscript
NSAppointment thing;
AppointmentPrivate private;
thing.SetPrivate(private);
```
