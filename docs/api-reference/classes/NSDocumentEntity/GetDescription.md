---
uid: crmscript_ref_NSDocumentEntity_GetDescription
title: String GetDescription()
intellisense: NSDocumentEntity.GetDescription
keywords: NSDocumentEntity, GetDescription
so.topic: reference
---

# String GetDescription()

The actual text, max 2047 significant characters even though it is stored as a larger data type on some databases

**Returns:** String

```crmscript
NSDocumentEntity thing;
String description  = thing.GetDescription();
```

