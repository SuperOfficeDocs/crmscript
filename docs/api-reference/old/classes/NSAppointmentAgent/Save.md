---
uid: crmscript_ref_NSAppointmentAgent_Save
title: NSAppointmentEntity Save(NSAppointmentEntity appointmentEntity, Integer updateMode, Bool sendEmailToParticipants, NSEMailConnectionInfo smtpEMailConnectionInfo, NSEMailConnectionInfo imapEMailConnectionInfo)
intellisense: NSAppointmentAgent.Save
keywords: NSAppointmentAgent, Save
so.topic: reference
---

# NSAppointmentEntity Save(NSAppointmentEntity appointmentEntity, Integer updateMode, Bool sendEmailToParticipants, NSEMailConnectionInfo smtpEMailConnectionInfo, NSEMailConnectionInfo imapEMailConnectionInfo)

Saving a booking.

**Returns:** NSAppointmentEntity

## Parameters

| Parameter | Type |Description |
|---|---|---|
| appointmentEntity | NSAppointmentEntity | |
| updateMode | Integer | Update mode for a recurring appointment. Enum: 0 = Unknown, 1 = OnlyThis, 2 = ThisAndForward, 9 = StopRecurrence |
| sendEmailToParticipants | Bool | If true, emails will be sent to all participants that is marked with send email flag. If false no mails will be sent even if the send email flag is true. |
| smtpEMailConnectionInfo| NSEMailConnectionInfo | Login information for outgoing smtp email server. Will be null if no login information is relevant. |
| imapEMailConnectionInfo| NSEMailConnectionInfo | Login information for imap server. Will be null if no login information is relevant. |

## Example

```crmscript
NSAppointmentAgent agent;
NSAppointmentEntity appointmentEntity;
Integer updateMode;
Bool sendEmailToParticipants;
NSEMailConnectionInfo smtpEMailConnectionInfo;
NSEMailConnectionInfo imapEMailConnectionInfo;
NSAppointmentEntity res = agent.Save(appointmentEntity, updateMode, sendEmailToParticipants, smtpEMailConnectionInfo, imapEMailConnectionInfo);
```
