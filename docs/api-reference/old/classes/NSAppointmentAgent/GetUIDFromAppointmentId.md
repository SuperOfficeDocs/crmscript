---
uid: crmscript_ref_NSAppointmentAgent_GetUIDFromAppointmentId
title: String GetUIDFromAppointmentId(Integer appointmentId, Bool useMotherId)
intellisense: NSAppointmentAgent.GetUIDFromAppointmentId
keywords: NSAppointmentAgent, GetUIDFromAppointmentId
so.topic: reference
---

# String GetUIDFromAppointmentId(Integer appointmentId, Bool useMotherId)

Get the UID associated with the appointment id in the Invitation table.

**Returns:** The associated UID, or null if none exist.

## Parameters

| Parameter | Type |Description |
|---|---|---|
| appointmentId | Integer | |
| useMotherId | Bool | Uses motherId if no UID is found for appointmentId. |

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
Bool useMotherId;
String res = agent.GetUIDFromAppointmentId(appointmentId, useMotherId);
```
