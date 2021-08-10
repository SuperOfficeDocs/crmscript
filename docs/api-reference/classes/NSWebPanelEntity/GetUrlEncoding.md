---
uid: crmscript_ref_NSWebPanelEntity_GetUrlEncoding
title: Integer GetUrlEncoding()
intellisense: NSWebPanelEntity.GetUrlEncoding
keywords: NSWebPanelEntity, GetUrlEncoding
so.topic: reference
---

# Integer GetUrlEncoding()

The encoding of the URL

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = None 
     - Enum: 2 = ANSI 
     - Enum: 3 = Unicode 

```crmscript
NSWebPanelEntity thing;
Integer urlEncoding  = thing.GetUrlEncoding();
```

