---
uid: crmscript_ref_NSAppointmentAgent_Move
title: NSAppointmentEntity Move(Integer appointmentId, DateTime newStartTime, Integer updateMode)
intellisense: NSAppointmentAgent.Move
keywords: NSAppointmentAgent, Move
so.topic: reference
---

# NSAppointmentEntity Move(Integer appointmentId, DateTime newStartTime, Integer updateMode)

Moving a booking to another start time.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **newStartTime** The new start time for the moved booking.
* **updateMode** Update mode for a recurring appointment.

**Returns:** NSAppointmentEntity

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
DateTime newStartTime;
Integer updateMode;
NSAppointmentEntity res = agent.Move(appointmentId, newStartTime, updateMode);
```
