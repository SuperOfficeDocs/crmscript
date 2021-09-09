---
uid: crmscript_ref_NSAppointmentAgent_SetSeen
title: Void SetSeen(Integer appointmentId, Integer updateMode)
intellisense: NSAppointmentAgent.SetSeen
keywords: NSAppointmentAgent, SetSeen
so.topic: reference
---

# Void SetSeen(Integer appointmentId, Integer updateMode)

Sets an appointment invitation to seen.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **updateMode** Update mode for a recurring appointment.

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence
