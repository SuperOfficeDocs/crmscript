---
uid: crmscript_ref_NSAlarmData_SetBookingType
title: SetBookingType(Integer bookingType)
intellisense: NSAlarmData.SetBookingType
keywords: NSAlarmData, GetBookingType
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
NSAlarmData thing;
Integer bookingType;
thing.SetBookingType(bookingType);
```

