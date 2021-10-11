---
uid: crmscript_ref_NSAppointmentAgent_AssignTo
title: NSAppointmentEntity AssignTo(Integer appointmentId, ParticipantInfo participant, Integer updateMode)
intellisense: NSAppointmentAgent.AssignTo
keywords: NSAppointmentAgent, AssignTo
so.topic: reference
---

# NSAppointmentEntity AssignTo(Integer appointmentId, ParticipantInfo participant, Integer updateMode)

Assigning an appointment to another person.

**Returns:** Updated NSAppointmentEntity

## Parameters

| Parameter | Type |Description |
|---|---|---|
| appointmentId | Integer | The appointmentId. Both master and child record ids are accepted. |
| participant | ParticipantInfo | |
| updateMode | Integer | Update mode for a recurring appointment. |

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
ParticipantInfo participant;
Integer updateMode;
NSAppointmentEntity res = agent.AssignTo(appointmentId, participant, updateMode);
```