---
uid: crmscript_ref_NSAppointmentAgent_CreateDefaultAppointmentEntityFromSaleSuggestion
title: NSAppointmentEntity CreateDefaultAppointmentEntityFromSaleSuggestion(Integer suggestedAppointmentId, Integer saleId, Bool createNow, Integer ownerId)
intellisense: NSAppointmentAgent.CreateDefaultAppointmentEntityFromSaleSuggestion
keywords: NSAppointmentAgent, CreateDefaultAppointmentEntityFromSaleSuggestion
so.topic: reference
---

# NSAppointmentEntity CreateDefaultAppointmentEntityFromSaleSuggestion(Integer suggestedAppointmentId, Integer saleId, Bool createNow, Integer ownerId)

Creates an appointment based on a suggested appointment.

**Returns:** The newly created appointment

## Parameters

| Parameter | Type |Description |
|---|---|---|
| suggestedAppointmentId | Integer | The id of the suggested appointment |
| saleId | Integer | This is the id of the sale the appointment is connected to. This will be used to give the appointment it's starting date. If the id is 0 or invalid, we assume the start date is now |
| createNow | Bool | If this parameter is true, we override the suggested start time and create the appointment with the current date and time |
| ownerId | Integer | |

## Example

```crmscript
NSAppointmentAgent agent;
Integer suggestedAppointmentId;
Integer saleId;
Bool createNow;
Integer ownerId;
NSAppointmentEntity res = agent.CreateDefaultAppointmentEntityFromSaleSuggestion(suggestedAppointmentId, saleId, createNow, ownerId);
```
