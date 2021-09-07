---
uid: crmscript_ref_NSAppointment_GetCompleted
title: Integer GetCompleted()
intellisense: NSAppointment.GetCompleted
keywords: NSAppointment, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

The Completed state.

**Returns:** Integer

## Enum: Completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSAppointment thing;
Integer completed  = thing.GetCompleted();
```
