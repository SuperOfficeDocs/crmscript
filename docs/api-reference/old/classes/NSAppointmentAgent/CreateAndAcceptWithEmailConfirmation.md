---
uid: crmscript_ref_NSAppointmentAgent_CreateAndAcceptWithEmailConfirmation
title: Void CreateAndAcceptWithEmailConfirmation(Integer emailItemId, Integer updateMode)
intellisense: NSAppointmentAgent.CreateAndAcceptWithEmailConfirmation
keywords: NSAppointmentAgent, CreateAndAcceptWithEmailConfirmation
so.topic: reference
---

# Void CreateAndAcceptWithEmailConfirmation(Integer emailItemId, Integer updateMode)

Creating an appointment from an emailItem invitation and accepting it with email confirmation to the meeting organizer.

## Parameters

* **emailItemId** The emailItemId
* **updateMode** Update mode for a recurring appointment.

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence
