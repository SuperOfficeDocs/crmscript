---
uid: crmscript_ref_NSFormSubmissionEntity_SetStatus
title: SetStatus(Integer status)
intellisense: NSFormSubmissionEntity.SetStatus
keywords: NSFormSubmissionEntity, GetStatus
so.topic: reference
---

# SetStatus(Integer status)

What is the status of this submission

**Parameter:** 
 - **status** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = InProgress 
     - Enum: 2 = EmailVerification 
     - Enum: 3 = Submitted 
     - Enum: 4 = Processed 
     - Enum: 5 = Failed 

```crmscript
NSFormSubmissionEntity thing;
Integer status;
thing.SetStatus(status);
```

