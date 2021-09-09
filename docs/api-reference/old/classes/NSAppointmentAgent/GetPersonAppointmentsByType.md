---
uid: crmscript_ref_NSAppointmentAgent_GetPersonAppointmentsByType
title: NSAppointment[] GetPersonAppointmentsByType(Integer personId, Bool includeProjectAppointments, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)
intellisense: NSAppointmentAgent.GetPersonAppointmentsByType
keywords: NSAppointmentAgent, GetPersonAppointmentsByType
so.topic: reference
---

# NSAppointment[] GetPersonAppointmentsByType(Integer personId, Bool includeProjectAppointments, DateTime startTime, DateTime endTime, Integer count, Integer appointmentType)

Method that returns a specified number of appointments of a specific appointment type within a time range. The appointments belong to the person specified.

## Parameters

* **personId** The person id of the SuperOffice user (associate).
* **includeProjectAppointments** If true, all appointments that belong to projects where the user is a project member are included as well as the appointments belonging to the person.
* **startTime** The start of the time interval we want appointments from. This will usually be the current time.
* **endTime** The end of the time interval.
* **count** The maximum number of appointments that should be returned. -1 means no count restrictions.
* **appointmentType** The appointment type, e.g. inDiary, inChecklist etc.

### Enum: appointmentType

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
Bool includeProjectAppointments;
DateTime startTime;
DateTime endTime;
Integer count;
Integer appointmentType;
NSAppointment[] res = agent.GetPersonAppointmentsByType(personId, includeProjectAppointments, startTime, endTime, count, appointmentType);
```
