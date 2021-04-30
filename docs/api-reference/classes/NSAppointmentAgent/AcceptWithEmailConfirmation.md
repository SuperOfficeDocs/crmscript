﻿---
uid: crmscript_ref_NSAppointmentAgent_AcceptWithEmailConfirmation
title: Void AcceptWithEmailConfirmation(Integer appointmentId, Integer updateMode)
intellisense: NSAppointmentAgent.AcceptWithEmailConfirmation
keywords: NSAppointmentAgent, AcceptWithEmailConfirmation
so.topic: reference
---

Accepting an appointment invitation and send an email confirmation to the meeting organizer.

**Parameters:**
 - **appointmentId** The appointmentId. Both master and child record ids are accepted.
 - **updateMode** Update mode for a recurring appointment.
     - Enum: 0 = Unknown 
     - Enum: 1 = OnlyThis 
     - Enum: 2 = ThisAndForward 
     - Enum: 9 = StopRecurrence 

**Returns:** Updated AppointmentEntity

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
Integer updateMode;
Void res = agent.AcceptWithEmailConfirmation(appointmentId, updateMode);
```
