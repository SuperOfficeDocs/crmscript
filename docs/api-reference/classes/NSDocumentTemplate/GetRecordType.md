---
uid: crmscript_ref_NSDocumentTemplate_GetRecordType
title: NSDocTmplType GetRecordType()
intellisense: NSDocumentTemplate.GetRecordType
keywords: NSDocumentTemplate, GetRecordType
so.topic: reference
---

# NSDocTmplType GetRecordType()

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo* see EAppntRecordTypes

**Returns:** NSDocTmplType

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
NSDocumentTemplate thing;
NSDocTmplType recordType  = thing.GetRecordType();
```
