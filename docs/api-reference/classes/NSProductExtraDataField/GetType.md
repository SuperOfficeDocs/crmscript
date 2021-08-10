---
uid: crmscript_ref_NSProductExtraDataField_GetType
title: Integer GetType()
intellisense: NSProductExtraDataField.GetType
keywords: NSProductExtraDataField, GetType
so.topic: reference
---

# Integer GetType()

String, url, image. How the value should be interpreted.

**Returns:** Integer

     - Enum: 0 = String 
     - Enum: 1 = Url 
     - Enum: 2 = Image 

```crmscript
NSProductExtraDataField thing;
Integer type  = thing.GetType();
```

