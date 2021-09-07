---
uid: crmscript_ref_NSAppointment_SetBookingType
title: SetBookingType(Integer bookingType)
intellisense: NSAppointment.SetBookingType
keywords: NSAppointment, GetBookingType
so.topic: reference
---

# SetBookingType(Integer bookingType)

The type of booking the appointment represents

## Parameters

* **bookingType** Integer

### bookingType

* 0 = Unknown
* 1 = None
* 2 = Owner
* 3 = Participant

## Example

```crmscript
NSAppointment thing;
Integer bookingType;
thing.SetBookingType(bookingType);
```
