---
uid: crmscript_ref_NSAlarmData_GetAssignmentStatus
title: Integer GetAssignmentStatus()
intellisense: NSAlarmData.GetAssignmentStatus
keywords: NSAlarmData, GetAssignmentStatus
so.topic: reference
---

# Integer GetAssignmentStatus()

Status if this appointment is in the process of being assigned to someone else

**Returns:** Integer

## Enum: assignment status

* 0 = Unknown
* 1 = None
* 11 = Assigning
* 12 = Seen
* 13 = Declined

## Example

```crmscript
NSAlarmData thing;
Integer assignmentStatus  = thing.GetAssignmentStatus();
```
