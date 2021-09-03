---
uid: crmscript_ref_NSAppointmentAgent_ValidateDays
title: NSRecurrenceDate[] ValidateDays(NSAppointmentEntity appointmentEntity, DateTime[] dates)
intellisense: NSAppointmentAgent.ValidateDays
keywords: NSAppointmentAgent, ValidateDays
so.topic: reference
---

# NSRecurrenceDate[] ValidateDays(NSAppointmentEntity appointmentEntity, DateTime[] dates)

Validates the set of dates to calculate any conflicts.

**Returns:** NSRecurrenceDate[]

## Parameters

| Parameter | Types | Description |
|---|---|---|
| appointmentEntity | NSappointmentEntity | |
| dates | DateTime[] | The dates to validate. |

## Example

```crmscript
NSAppointmentAgent agent;
NSAppointmentEntity appointmentEntity;
DateTime[] dates;
NSRecurrenceDate[] res = agent.ValidateDays(appointmentEntity, dates);
```
