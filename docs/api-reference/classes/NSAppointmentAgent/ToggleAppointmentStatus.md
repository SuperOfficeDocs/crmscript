---
uid: crmscript_ref_NSAppointmentAgent_ToggleAppointmentStatus
title: Integer ToggleAppointmentStatus(Integer appointmentId)
intellisense: NSAppointmentAgent.ToggleAppointmentStatus
keywords: NSAppointmentAgent, ToggleAppointmentStatus
so.topic: reference
---

# Integer ToggleAppointmentStatus(Integer appointmentId)

Sets an appointment's status to Completed if the appointment had a different status, or sets the status to started if already set to completed.

**Parameters:**
 - **appointmentId** The appointment id.

**Returns:** The new AppointmentStatus

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
Integer res = agent.ToggleAppointmentStatus(appointmentId);
```

