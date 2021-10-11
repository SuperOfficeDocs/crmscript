---
uid: crmscript_ref_NSAppointmentEntity_SetAssignmentStatus
title: SetAssignmentStatus(Integer assignmentStatus)
intellisense: NSAppointmentEntity.SetAssignmentStatus
keywords: NSAppointmentEntity, GetAssignmentStatus
so.topic: reference
---

# SetAssignmentStatus(Integer assignmentStatus)

Status if this appointment is in the process of being assigned to someone else

## Parameters

* **assignmentStatus** Integer

### Enum: assignmentStatus

* 0 = Unknown
* 1 = None
* 11 = Assigning
* 12 = Seen
* 13 = Declined

## Example

```crmscript
NSAppointmentEntity thing;
Integer assignmentStatus;
thing.SetAssignmentStatus(assignmentStatus);
```