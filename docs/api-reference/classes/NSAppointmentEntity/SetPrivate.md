---
uid: crmscript_ref_NSAppointmentEntity_SetPrivate
title: SetPrivate(Integer private)
intellisense: NSAppointmentEntity.SetPrivate
keywords: NSAppointmentEntity, GetPrivate
so.topic: reference
---

# SetPrivate(Integer private)

The confidentiality of appointments is shown as different types of “private” on the appointment. For an updated list of “private” types, see the database manual.

**Parameter:** 
 - **private** Integer
     - Enum: 0 = Public 
     - Enum: 1 = PrivateUser 
     - Enum: 2 = PrivateGroup 

```crmscript
NSAppointmentEntity thing;
Integer private;
thing.SetPrivate(private);
```

