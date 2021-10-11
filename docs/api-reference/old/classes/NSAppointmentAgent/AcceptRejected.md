---
uid: crmscript_ref_NSAppointmentAgent_AcceptRejected
title: NSAppointmentEntity AcceptRejected(Integer appointmentId, Integer updateMode)
intellisense: NSAppointmentAgent.AcceptRejected
keywords: NSAppointmentAgent, AcceptRejected
so.topic: reference
---

# NSAppointmentEntity AcceptRejected(Integer appointmentId, Integer updateMode)

Accept that an invited participant has rejected your invitation or assignment.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
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
Integer updateMode;
NSAppointmentEntity res = agent.AcceptRejected(appointmentId, updateMode);
```