﻿---
uid: crmscript_ref_NSAppointmentAgent_CreateAppointmentForUID
title: AppointmentEntity CreateAppointmentForUID(AppointmentEntity appointmentEntity, String uID)
intellisense: NSAppointmentAgent.CreateAppointmentForUID
keywords: NSAppointmentAgent, CreateAppointmentForUID
so.topic: reference
---

Create an invitation record and an appointment with a given UID to reserve it if the UID is unused, otherwise null.

**Parameters:**
 - **appointmentEntity** 
 - **uID** The UID associated with the appointment

**Returns:** The newly created AppointmentEntity or null if the UID is in the DB already.

```crmscript
NSAppointmentAgent agent;
AppointmentEntity appointmentEntity;
String uID;
AppointmentEntity res = agent.CreateAppointmentForUID(appointmentEntity, uID);
```
