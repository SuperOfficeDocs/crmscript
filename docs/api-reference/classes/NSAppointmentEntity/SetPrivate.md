---
uid: crmscript_ref_NSAppointmentEntity_SetPrivate
title: SetPrivate(Integer private)
intellisense: NSAppointmentEntity.SetPrivate
keywords: NSAppointmentEntity, GetPrivate
so.topic: reference
---

# SetPrivate(Integer private)

The confidentiality of appointments is shown as different types of "private" on the appointment. For an updated list of "private" types, see the database manual.

## Parameters

* **private** Integer

### Enum: AppointmentPrivate

* 0 = Public
* 1 = PrivateUser
* 2 = PrivateGroup

## Example

```crmscript
NSAppointmentEntity thing;
Integer private;
thing.SetPrivate(private);
```
