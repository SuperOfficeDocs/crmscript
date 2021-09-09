---
uid: crmscript_ref_NSAppointment_SetTaskType
title: SetTaskType(Integer taskType)
intellisense: NSAppointment.SetTaskType
keywords: NSAppointment, GetTaskType
so.topic: reference
---

# SetTaskType(Integer taskType)

The different task types of the appointment, if the activity is an appointment, task, phone. See the different types of appointments in the database manual.

## Parameters

* **taskType** Integer

### Enum: TaskType

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
Integer taskType;
thing.SetTaskType(taskType);
```
