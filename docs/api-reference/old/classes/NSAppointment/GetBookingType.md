---
uid: crmscript_ref_NSAppointment_GetBookingType
title: Integer GetBookingType()
intellisense: NSAppointment.GetBookingType
keywords: NSAppointment, GetBookingType
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
NSAppointment thing;
Integer bookingType  = thing.GetBookingType();
```
