---
uid: crmscript_ref_NSSaleEntity_GetPostit
title: String GetPostit()
intellisense: NSSaleEntity.GetPostit
keywords: NSSaleEntity, GetPostit
so.topic: reference
---

# String GetPostit()

The actual text, max 2047 significant characters even though it is stored as a larger data type on some databases

**Returns:** String

```crmscript
NSSaleEntity thing;
String postit  = thing.GetPostit();
```

