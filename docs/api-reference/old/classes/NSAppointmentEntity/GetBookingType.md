---
uid: crmscript_ref_NSAppointmentEntity_GetBookingType
title: Integer GetBookingType()
intellisense: NSAppointmentEntity.GetBookingType
keywords: NSAppointmentEntity, GetBookingType
so.topic: reference
---

# Integer GetBookingType()

The type of booking the appointment represents

**Returns:** Integer

## Enum: bookingType

* 0 = Unknown
* 1 = None
* 2 = Owner
* 3 = Participant

## Example

```crmscript
NSAppointmentEntity thing;
Integer bookingType  = thing.GetBookingType();
```
