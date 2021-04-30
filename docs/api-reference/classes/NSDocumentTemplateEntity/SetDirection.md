﻿---
uid: crmscript_ref_NSDocumentTemplateEntity_SetDirection
title: SetDirection(DocTmplDirection direction)
intellisense: NSDocumentTemplateEntity.SetDirection
keywords: NSDocumentTemplateEntity, GetDirection
so.topic: reference
---

1 = incoming, 2 = outgoing, see EAppntDirection

**Parameter:** 
 - **direction** DocTmplDirection
     - Enum: 0 = Unknown 
     - Enum: 1 = Incoming 
     - Enum: 2 = Outgoing 
     - Enum: 3 = SaintAll 

```crmscript
NSDocumentTemplateEntity thing;
DocTmplDirection direction;
thing.SetDirection(direction);
```
