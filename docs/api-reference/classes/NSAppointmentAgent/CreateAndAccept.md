---
uid: crmscript_ref_NSAppointmentAgent_CreateAndAccept
title: Void CreateAndAccept(Integer emailItemId, Integer updateMode)
intellisense: NSAppointmentAgent.CreateAndAccept
keywords: NSAppointmentAgent, CreateAndAccept
so.topic: reference
---

# Void CreateAndAccept(Integer emailItemId, Integer updateMode)

Creating an appointment from an emailItem invitation and accepting it.

## Parameters

* **emailItemId** The emailItemId
* **updateMode** Update mode for a recurring appointment.

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence
