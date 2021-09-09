---
uid: crmscript_ref_NSTaskListItem_SetType
title: SetType(Integer type)
intellisense: NSTaskListItem.SetType
keywords: NSTaskListItem, GetType
so.topic: reference
---

# SetType(Integer type)

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo* see EAppntRecordTypes

## Parameters

* **type** Integer

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
NSTaskListItem thing;
TaskType type;
thing.SetType(type);
```
