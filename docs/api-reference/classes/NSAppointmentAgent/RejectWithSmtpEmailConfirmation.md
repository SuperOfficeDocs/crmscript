---
uid: crmscript_ref_NSAppointmentAgent_RejectWithSmtpEmailConfirmation
title: Void RejectWithSmtpEmailConfirmation(Integer appointmentId, String rejectReason, Integer updateMode, NSEMailConnectionInfo smtpEMailConnectionInfo)
intellisense: NSAppointmentAgent.RejectWithSmtpEmailConfirmation
keywords: NSAppointmentAgent, RejectWithSmtpEmailConfirmation
so.topic: reference
---

# Void RejectWithSmtpEmailConfirmation(Integer appointmentId, String rejectReason, Integer updateMode, NSEMailConnectionInfo smtpEMailConnectionInfo)

Rejecting an appointment invitation and send an email confirmation to the meeting organizer.

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **rejectReason** The reason the invitation was rejected.
* **updateMode** Update mode for a recurring appointment.
* **smtpEMailConnectionInfo** Login information for outgoing smtp email server. Will be null if no login information is relevant.

**Returns:** NSAppointmentEntity

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence

## Example

```crmscript
NSAppointmentAgent agent;
Integer appointmentId;
String rejectReason;
Integer updateMode;
NSEMailConnectionInfo smtpEMailConnectionInfo;
agent.RejectWithSmtpEmailConfirmation(appointmentId, rejectReason, updateMode, smtpEMailConnectionInfo);
```
