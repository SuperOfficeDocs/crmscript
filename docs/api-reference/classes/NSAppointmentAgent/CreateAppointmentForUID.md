---
uid: crmscript_ref_NSAppointmentAgent_CreateAppointmentForUID
title: NSAppointmentEntity CreateAppointmentForUID(NSAppointmentEntity appointmentEntity, String uID)
intellisense: NSAppointmentAgent.CreateAppointmentForUID
keywords: NSAppointmentAgent, CreateAppointmentForUID
so.topic: reference
---

# NSAppointmentEntity CreateAppointmentForUID(NSAppointmentEntity appointmentEntity, String uID)

Create an invitation record and an appointment with a given UID to reserve it if the UID is unused, otherwise null.

**Returns:** The newly created NSAppointmentEntity or null if the UID is in the DB already.

## Parameters

| Parameter | Type |Description |
|---|---|---|
| appointmentEntity | NSAppointmentEntity | |
| uID | String | The UID associated with the appointment |

## Example

```crmscript
NSAppointmentAgent agent;
NSAppointmentEntity appointmentEntity;
String uID;
NSAppointmentEntity res = agent.CreateAppointmentForUID(appointmentEntity, uID);
```
