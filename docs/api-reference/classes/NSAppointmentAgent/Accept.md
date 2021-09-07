---
uid: crmscript_ref_NSAppointmentAgent_Accept
title: Void Accept(Integer appointmentId, Integer updateMode)
intellisense: NSAppointmentAgent.Accept
keywords: NSAppointmentAgent, Accept
so.topic: reference
---

# Void Accept(Integer appointmentId, Integer updateMode)

Accepting an appointment invitation.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **updateMode** Update mode for a recurring appointment.

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence

**Returns:** Updated NSAppointmentEntity

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
Integer updateMode;
agent.Accept(appointmentId, updateMode);
```
