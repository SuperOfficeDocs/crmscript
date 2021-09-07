---
uid: crmscript_ref_NSAppointmentAgent_GetProjectMemberAppointmentsByType
title: NSAppointment[] GetProjectMemberAppointmentsByType(Integer personId, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)
intellisense: NSAppointmentAgent.GetProjectMemberAppointmentsByType
keywords: NSAppointmentAgent, GetProjectMemberAppointmentsByType
so.topic: reference
---

# NSAppointment[] GetProjectMemberAppointmentsByType(Integer personId, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)

Method that returns a specified number of appointments of a specific appointment type within a time range. The appointments belong to the projects where the person specified is member.

## Parameters

* **personId** The project member's person id
* **startTime** The start of the time interval we want appointments from. This will usually be the current time.
* **endTime** The end of the time interval.
* **count** The maximum number of appointments that should be returned. -1 means no count restrictions.
* **appointmentType** The appointment type, e.g. inDiary, inChecklist etc.

### Enum: appointment type

* 0 = Unknown
* 1 = inDiary
* 2 = inChecklist
* 3 = Note
* 4 = Document
* 5 = SavedReport
* 6 = BookingForDiary
* 7 = BookingForChecklist
* 8 = MergeDraft
* 9 = MergeFinal

**Returns:** NSAppointment[]

## Example

```crmscript
NSAppointmentAgent agent;
Integer personId;
DateTime startTime;
DateTime endTime;
Integer count;
Integer appointmentType;
NSAppointment[] res = agent.GetProjectMemberAppointmentsByType(personId, startTime, endTime, count, appointmentType);
```
