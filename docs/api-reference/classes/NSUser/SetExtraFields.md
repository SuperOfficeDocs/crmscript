﻿---
uid: crmscript_ref_NSUser_SetExtraFields
title: SetExtraFields(Map extras)
intellisense: NSUser.SetExtraFields
keywords: NSUser, SetExtraFields
so.topic: reference
---

Set the extra field values on User with a map.

**Parameter:** 
 - **extras** Map

```crmscript
NSUser thing;
Map extras;
extras["SuperOffice:1"] = "[I:123]";
extras["SuperOffice:1"] = "123"; // this will also work, but beware of decimal point variations in different languages
extras["custom.progid"] = "foobar";
thing.SetExtraFields(extras);
```

