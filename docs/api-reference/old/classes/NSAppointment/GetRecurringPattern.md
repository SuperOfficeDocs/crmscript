---
uid: crmscript_ref_NSAppointment_GetRecurringPattern
title: Integer GetRecurringPattern()
intellisense: NSAppointment.GetRecurringPattern
keywords: NSAppointment, GetRecurringPattern
so.topic: reference
---

# Integer GetRecurringPattern()

**Returns:** Integer

## Enum: RecurringPattern

* 0 = Unknown
* 1 = Daily
* 2 = Weekly
* 3 = Monthly
* 4 = Yearly
* 5 = Custom

## Example

```crmscript
NSAppointment thing;
Integer recurringPattern  = thing.GetRecurringPattern();
```
