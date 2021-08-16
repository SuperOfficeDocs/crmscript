---
uid: crmscript_ref_NSAlarmData_GetBookingType
title: Integer GetBookingType()
intellisense: NSAlarmData.GetBookingType
keywords: NSAlarmData, GetBookingType
so.topic: reference
---

# Integer GetBookingType()

The type of booking the appointment represents

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = None 
     - Enum: 2 = Owner 
     - Enum: 3 = Participant 

```crmscript
NSAlarmData thing;
Integer bookingType  = thing.GetBookingType();
```

