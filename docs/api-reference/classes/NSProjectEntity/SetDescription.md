---
uid: crmscript_ref_NSProjectEntity_SetDescription
title: SetDescription(String description)
intellisense: NSProjectEntity.SetDescription
keywords: NSProjectEntity, GetDescription
so.topic: reference
---

# SetDescription(String description)

The actual text, max 2047 significant characters even though it is stored as a larger data type on some databases

**Parameter:** 
 - **description** String

```crmscript
NSProjectEntity thing;
String description;
thing.SetDescription(description);
```

