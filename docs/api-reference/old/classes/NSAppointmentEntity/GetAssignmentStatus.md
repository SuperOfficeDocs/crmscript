---
uid: crmscript_ref_NSAppointmentEntity_GetAssignmentStatus
title: Integer GetAssignmentStatus()
intellisense: NSAppointmentEntity.GetAssignmentStatus
keywords: NSAppointmentEntity, GetAssignmentStatus
so.topic: reference
---

# Integer GetAssignmentStatus()

Status if this appointment is in the process of being assigned to someone else

**Returns:** Integer

## Enum: assignmentStatus

* 0 = Unknown
* 1 = None
* 11 = Assigning
* 12 = Seen
* 13 = Declined

## Example

```crmscript
NSAppointmentEntity thing;
Integer assignmentStatus  = thing.GetAssignmentStatus();
```
