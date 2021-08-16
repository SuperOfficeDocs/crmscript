---
uid: crmscript_ref_NSSelectionEntity_GetPostit
title: String GetPostit()
intellisense: NSSelectionEntity.GetPostit
keywords: NSSelectionEntity, GetPostit
so.topic: reference
---

# String GetPostit()

The actual text, max 2047 significant characters even though it is stored as a larger data type on some databases

**Returns:** String

```crmscript
NSSelectionEntity thing;
String postit  = thing.GetPostit();
```

