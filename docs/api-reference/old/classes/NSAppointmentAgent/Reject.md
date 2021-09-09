---
uid: crmscript_ref_NSAppointmentAgent_Reject
title: Void Reject(Integer appointmentId, String rejectReason, Integer updateMode)
intellisense: NSAppointmentAgent.Reject
keywords: NSAppointmentAgent, Reject
so.topic: reference
---

# Void Reject(Integer appointmentId, String rejectReason, Integer updateMode)

Rejecting an appointment invitation

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **rejectReason** The reason the invitation was rejected.
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
String rejectReason;
Integer updateMode;
agent.Reject(appointmentId, rejectReason, updateMode);
```
