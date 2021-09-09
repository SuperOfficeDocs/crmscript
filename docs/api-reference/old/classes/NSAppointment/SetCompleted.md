---
uid: crmscript_ref_NSAppointment_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSAppointment.SetCompleted
keywords: NSAppointment, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Completed state.

## Parameters

* **completed** Integer

### Enum: completed state

* 0 = Unknown
* 1 = NotStarted
* 2 = Started
* 3 = Completed

## Example

```crmscript
NSAppointment thing;
Integer completed;
thing.SetCompleted(completed);
```
