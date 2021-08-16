---
uid: crmscript_ref_NSTaskListItem_GetType
title: Integer GetType()
intellisense: NSTaskListItem.GetType
keywords: NSTaskListItem, GetType
so.topic: reference
---

# Integer GetType()

1 = app, 2 = doc, 3 = email, 4 = fax, 5 = phone, 6 = todo - see EAppntRecordTypes

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = Appointment 
     - Enum: 2 = Document 
     - Enum: 3 = Email 
     - Enum: 4 = Fax 
     - Enum: 5 = Phone 
     - Enum: 6 = ToDo 
     - Enum: 7 = MailMergeDraft 
     - Enum: 8 = MailMergeFinal 
     - Enum: 9 = Report 
     - Enum: 10 = SaintAll 

```crmscript
NSTaskListItem thing;
Integer type  = thing.GetType();
```

