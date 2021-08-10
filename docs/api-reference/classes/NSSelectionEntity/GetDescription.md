---
uid: crmscript_ref_NSSelectionEntity_GetDescription
title: String GetDescription()
intellisense: NSSelectionEntity.GetDescription
keywords: NSSelectionEntity, GetDescription
so.topic: reference
---

# String GetDescription()

The actual text, max 2047 significant characters even though it is stored as a larger data type on some databases

**Returns:** String

```crmscript
NSSelectionEntity thing;
String description  = thing.GetDescription();
```

