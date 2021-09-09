---
uid: crmscript_ref_NSAppointmentAgent_AcceptWithSmtpEmailConfirmation
title: Void AcceptWithSmtpEmailConfirmation(Integer appointmentId, Integer updateMode, NSEMailConnectionInfo smtpEMailConnectionInfo)
intellisense: NSAppointmentAgent.AcceptWithSmtpEmailConfirmation
keywords: NSAppointmentAgent, AcceptWithSmtpEmailConfirmation
so.topic: reference
---

# Void AcceptWithSmtpEmailConfirmation(Integer appointmentId, Integer updateMode, NSEMailConnectionInfo smtpEMailConnectionInfo)

Accepting an appointment invitation and send an email confirmation to the meeting organizer.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **updateMode** Update mode for a recurring appointment.
* **smtpEMailConnectionInfo** Login information for outgoing smtp email server. Will be null if no login information is relevant.

**Returns:** Updated NSAppointmentEntity

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
Integer updateMode;
NSEMailConnectionInfo smtpEMailConnectionInfo;
agent.AcceptWithSmtpEmailConfirmation(appointmentId, updateMode, smtpEMailConnectionInfo);
```
