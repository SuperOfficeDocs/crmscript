﻿---
uid: crmscript_ref_NSContactEntity_SetUserDefinedFields
title: SetUserDefinedFields(Map udefs)
intellisense: NSContactEntity.SetUserDefinedFields
keywords: NSContactEntity, SetUserDefinedFields
so.topic: reference
---

Set the user-defined fields on the NSContactEntity as a map.

**Parameter:** 
 - **udefs** Map user defined field values encoded as strings.

```crmscript
NSContactEntity thing;
Map udefs;
udefs["SuperOffice:1"] = "[I:123]";
udefs["SuperOffice:1"] = "123"; // this will also work, but beware of decimal point variations in different languages
udefs["custom.progid"] = "foobar";
thing.SetUserDefinedFields(udefs);
```

