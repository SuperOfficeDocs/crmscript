---
uid: crmscript_ref_NSDocumentTemplateEntity_SetRecordType
title: SetRecordType(NSDocTmplType recordType)
intellisense: NSDocumentTemplateEntity.SetRecordType
keywords: NSDocumentTemplateEntity, GetRecordType
so.topic: reference
---

# SetRecordType(NSDocTmplType recordType)

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo* see EAppntRecordTypes

## Parameters

* **recordType** NSDocTmplType

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
NSDocumentTemplateEntity thing;
NSDocTmplType recordType;
thing.SetRecordType(recordType);
```
