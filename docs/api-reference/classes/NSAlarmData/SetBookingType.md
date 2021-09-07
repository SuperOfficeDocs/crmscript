---
uid: crmscript_ref_NSAlarmData_SetBookingType
title: SetBookingType(Integer bookingType)
intellisense: NSAlarmData.SetBookingType
keywords: NSAlarmData, GetBookingType
so.topic: reference
---

# SetBookingType(Integer bookingType)

The type of booking the appointment represents

## Parameters

* **bookingType** Integer

### Enum: bookingType

* 0 = Unknown
* 1 = None
* 2 = Owner
* 3 = Participant

## Example

```crmscript
NSAlarmData thing;
Integer bookingType;
thing.SetBookingType(bookingType);
```
