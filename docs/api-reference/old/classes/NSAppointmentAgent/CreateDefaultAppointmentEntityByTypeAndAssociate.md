---
uid: crmscript_ref_NSAppointmentAgent_CreateDefaultAppointmentEntityByTypeAndAssociate
title: NSAppointmentEntity CreateDefaultAppointmentEntityByTypeAndAssociate(Integer type, Integer associateId)
intellisense: NSAppointmentAgent.CreateDefaultAppointmentEntityByTypeAndAssociate
keywords: NSAppointmentAgent, CreateDefaultAppointmentEntityByTypeAndAssociate
so.topic: reference
---

# NSAppointmentEntity CreateDefaultAppointmentEntityByTypeAndAssociate(Integer type, Integer associateId)

Creates an NSAppointmentEntity populated with the default values for the specific type and owner.

## Parameters

* **type** The type of task requested.
* **associateId** The associateId of the appointment owner.

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
Integer associateId;
NSAppointmentEntity res = agent.CreateDefaultAppointmentEntityByTypeAndAssociate(type, associateId);
```
