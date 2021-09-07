---
uid: crmscript_ref_NSAppointmentEntity_GetPrivate
title: Integer GetPrivate()
intellisense: NSAppointmentEntity.GetPrivate
keywords: NSAppointmentEntity, GetPrivate
so.topic: reference
---

# Integer GetPrivate()

The confidentiality of appointments is shown as different types of "private" on the appointment. For an updated list of "private" types, see the database manual.

**Returns:** Integer

## Enum: AppointmentPrivate

* 0 = Public
* 1 = PrivateUser
* 2 = PrivateGroup

## Example

```crmscript
NSAppointmentEntity thing;
Integer private  = thing.GetPrivate();
```
