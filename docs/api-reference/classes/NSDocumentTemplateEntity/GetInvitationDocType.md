---
uid: crmscript_ref_NSDocumentTemplateEntity_GetInvitationDocType
title: NSDocTmplInvitationType GetInvitationDocType()
intellisense: NSDocumentTemplateEntity.GetInvitationDocType
keywords: NSDocumentTemplateEntity, GetInvitationDocType
so.topic: reference
---

# NSDocTmplInvitationType GetInvitationDocType()

Type for sending email meeting invitation. Not an invitation type template = 0, New = 1, Changed = 2, Cancelled = 3

**Returns:** NSDocTmplInvitationType

     - Enum: 0 = None 
     - Enum: 1 = New 
     - Enum: 2 = Changed 
     - Enum: 3 = Cancelled 

```crmscript
NSDocumentTemplateEntity thing;
NSDocTmplInvitationType invitationDocType  = thing.GetInvitationDocType();
```

