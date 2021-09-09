---
uid: crmscript_ref_NSAppointmentAgent_CreateDefaultAppointmentEntityByType
title: NSAppointmentEntity CreateDefaultAppointmentEntityByType(Integer type)
intellisense: NSAppointmentAgent.CreateDefaultAppointmentEntityByType
keywords: NSAppointmentAgent, CreateDefaultAppointmentEntityByType
so.topic: reference
---

# NSAppointmentEntity CreateDefaultAppointmentEntityByType(Integer type)

Creates an NSAppointmentEntity populated with the default values for the specific type.

## Parameters

* **type** The type of task requested.

**Returns:** NSAppointmentEntity with default values.

### Enum: AppntRecordTypes

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
NSAppointmentAgent agent;
Integer type;
NSAppointmentEntity res = agent.CreateDefaultAppointmentEntityByType(type);
```
