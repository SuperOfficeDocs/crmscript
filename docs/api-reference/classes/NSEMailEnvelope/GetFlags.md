---
uid: crmscript_ref_NSEMailEnvelope_GetFlags
title: Integer GetFlags()
intellisense: NSEMailEnvelope.GetFlags
keywords: NSEMailEnvelope, GetFlags
so.topic: reference
---

# Integer GetFlags()

Flag status of this mail (unread, replied, deleted )

**Returns:** Integer

     - Enum: 0 = None 
     - Enum: 1 = Seen 
     - Enum: 2 = Deleted 
     - Enum: 4 = Recent 
     - Enum: 8 = Flagged 
     - Enum: 16 = Draft 
     - Enum: 32 = Answered 

```crmscript
NSEMailEnvelope thing;
Integer flags  = thing.GetFlags();
```

