---
uid: crmscript_ref_NSAppointment_SetRecurringPattern
title: SetRecurringPattern(Integer recurringPattern)
intellisense: NSAppointment.SetRecurringPattern
keywords: NSAppointment, GetRecurringPattern
so.topic: reference
---

# SetRecurringPattern(Integer recurringPattern)

## Parameters

* **recurringPattern** Integer

### Enum: RecurringPattern

* 0 = Unknown
* 1 = Daily
* 2 = Weekly
* 3 = Monthly
* 4 = Yearly
* 5 = Custom

## Example

```crmscript
NSAppointment thing;
Integer recurringPattern;
thing.SetRecurringPattern(recurringPattern);
```
