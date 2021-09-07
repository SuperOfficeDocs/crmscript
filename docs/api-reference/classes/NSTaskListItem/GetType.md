---
uid: crmscript_ref_NSTaskListItem_GetType
title: Integer GetType()
intellisense: NSTaskListItem.GetType
keywords: NSTaskListItem, GetType
so.topic: reference
---

# Integer GetType()

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo* see EAppntRecordTypes

**Returns:** Integer

## Enum: AppntRecordTypes

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
Integer type  = thing.GetType();
```
