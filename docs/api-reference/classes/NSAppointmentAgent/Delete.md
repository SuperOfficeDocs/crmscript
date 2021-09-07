---
uid: crmscript_ref_NSAppointmentAgent_Delete
title: Void Delete(Integer appointmentId, Integer updateMode, Bool sendEmailToParticipants, NSEMailConnectionInfo smtpEMailConnectionInfo, NSEMailConnectionInfo imapEMailConnectionInfo)
intellisense: NSAppointmentAgent.Delete
keywords: NSAppointmentAgent, Delete
so.topic: reference
---

# Void Delete(Integer appointmentId, Integer updateMode, Bool sendEmailToParticipants, NSEMailConnectionInfo smtpEMailConnectionInfo, NSEMailConnectionInfo imapEMailConnectionInfo)

Deleting a booking

## Parameters

* **appointmentId** The appointmentId. Both master and child record ids are accepted.
* **updateMode** Update mode for a recurring appointment.
* **sendEmailToParticipants** If true, emails will be sent to all participants that is marked with send email flag. If false no mails will be sent even if the send email flag is true.
* **smtpEMailConnectionInfo** Login information for outgoing smtp email server. Will be null if no login information is relevant.
* **imapEMailConnectionInfo** Login information for imap server. Will be null if no login information is relevant.

### Enum updateMode

* 0 = Unknown
* 1 = OnlyThis
* 2 = ThisAndForward
* 9 = StopRecurrence
