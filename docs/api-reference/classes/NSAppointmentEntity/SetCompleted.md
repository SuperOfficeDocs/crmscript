---
uid: crmscript_ref_NSAppointmentEntity_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSAppointmentEntity.SetCompleted
keywords: NSAppointmentEntity, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

Appointment Completed state. This property is the part of the Status property that is the completed state. Could be three state if the three state user preference is set.

## Parameters

* **completed** Integer

## Example

```crmscript
NSAppointmentEntity thing;
Integer completed;
thing.SetCompleted(completed);
```
