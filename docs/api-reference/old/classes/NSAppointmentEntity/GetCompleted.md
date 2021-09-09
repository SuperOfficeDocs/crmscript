---
uid: crmscript_ref_NSAppointmentEntity_GetCompleted
title: Integer GetCompleted()
intellisense: NSAppointmentEntity.GetCompleted
keywords: NSAppointmentEntity, GetCompleted
so.topic: reference
---

# Integer GetCompleted()

Appointment Completed state. This property is the part of the Status property that is the completed state. Could be three state if the three state user preference is set.

**Returns:** Integer

## Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSAppointmentEntity thing;
Integer completed  = thing.GetCompleted();
```
