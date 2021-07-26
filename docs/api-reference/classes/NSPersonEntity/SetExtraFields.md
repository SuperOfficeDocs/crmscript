﻿---
uid: crmscript_ref_NSPersonEntity_SetExtraFields
title: SetExtraFields(Map extras)
intellisense: NSPersonEntity.SetExtraFields
keywords: NSPersonEntity, SetExtraFields
so.topic: reference
---

Set the extra field values on NSPersonEntity with a map.

**Parameter:** 
 - **extras** Map containing extra field values encoded as strings.

```crmscript
NSPersonEntity thing;
Map extras;
extras["SuperOffice:1"] = "[I:123]";
extras["SuperOffice:1"] = "123"; // this will also work, but beware of decimal point variations in different languages
extras["custom.progid"] = "foobar";
thing.SetExtraFields(extras);
```

