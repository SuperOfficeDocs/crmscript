---
uid: crmscript_ref_NSAppointmentEntity_SetBookingType
title: SetBookingType(Integer bookingType)
intellisense: NSAppointmentEntity.SetBookingType
keywords: NSAppointmentEntity, GetBookingType
so.topic: reference
---

# SetBookingType(Integer bookingType)

The type of booking the appointment represents

**Parameter:** 
 - **bookingType** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = None 
     - Enum: 2 = Owner 
     - Enum: 3 = Participant 

```crmscript
NSAppointmentEntity thing;
Integer bookingType;
thing.SetBookingType(bookingType);
```

