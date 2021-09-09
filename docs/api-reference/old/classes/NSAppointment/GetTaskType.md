---
uid: crmscript_ref_NSAppointment_GetTaskType
title: Integer GetTaskType()
intellisense: NSAppointment.GetTaskType
keywords: NSAppointment, GetTaskType
so.topic: reference
---

# Integer GetTaskType()

The different task types of the appointment, if the activity is an appointment, task, phone. See the different types of appointments in the database manual.

**Returns:** Integer

## Enum: TaskType

* 0 = Unknown
* 1 = Appointment
* 2 = Document
* 3 = Email
* 4 = Fax
* 5 = Phone
* 6 = ToDo
* 7 = MailMergeDraft
* 8 = MailMergeFinal
* 9 = Report
* 10 = SaintAll

## Example

```crmscript
NSAppointment thing;
Integer taskType  = thing.GetTaskType();
```
