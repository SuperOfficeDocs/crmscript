---
uid: crmscript_ref_NSAppointment_SetIsBookingMain
title: SetIsBookingMain(Bool isBookingMain)
intellisense: NSAppointment.SetIsBookingMain
keywords: NSAppointment, GetIsBookingMain
so.topic: reference
---

# SetIsBookingMain(Bool isBookingMain)

True if this appointment is a booking and current associate is the owner. False if it is a booking and current associate is a participant.

**Parameter:** 
 - **isBookingMain** Bool

```crmscript
NSAppointment thing;
Bool isBookingMain;
thing.SetIsBookingMain(isBookingMain);
```

