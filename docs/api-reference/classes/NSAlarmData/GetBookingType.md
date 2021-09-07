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

## Enum: BookingType

* 0 = Unknown
* 1 = None
* 2 = Owner
* 3 = Participant

## Example
```crmscript
NSAlarmData thing;
Integer bookingType  = thing.GetBookingType();
```
