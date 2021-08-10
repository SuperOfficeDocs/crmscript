---
uid: crmscript_ref_NSEMailEnvelope_GetPriority
title: Integer GetPriority()
intellisense: NSEMailEnvelope.GetPriority
keywords: NSEMailEnvelope, GetPriority
so.topic: reference
---

# Integer GetPriority()

Importance of the e-mail

**Returns:** Integer

     - Enum: 0 = NoPriority 
     - Enum: 1 = Highest 
     - Enum: 2 = High 
     - Enum: 3 = Normal 
     - Enum: 4 = Low 
     - Enum: 5 = Lowest 

```crmscript
NSEMailEnvelope thing;
Integer priority  = thing.GetPriority();
```

