---
uid: crmscript_ref_NSAppointmentAgent_GetProjectAppointmentsByType
title: NSAppointment[] GetProjectAppointmentsByType(Integer projectId, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)
intellisense: NSAppointmentAgent.GetProjectAppointmentsByType
keywords: NSAppointmentAgent, GetProjectAppointmentsByType
so.topic: reference
---

# NSAppointment[] GetProjectAppointmentsByType(Integer projectId, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)

Method that returns a specified number of appointments of a specific appointment type within a time range. The appointments belong to the project specified.

## Parameters

* **projectId** The project id
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
Integer projectId;
DateTime startTime;
DateTime endTime;
Integer count;
Integer appointmentType;
NSAppointment[] res = agent.GetProjectAppointmentsByType(projectId, startTime, endTime, count, appointmentType);
```
