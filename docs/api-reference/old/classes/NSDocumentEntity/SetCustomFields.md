---
uid: crmscript_ref_NSDocumentEntity_SetCustomFields
title: SetCustomFields(Map udefs)
intellisense: NSDocumentEntity.SetCustomFields
keywords: NSDocumentEntity, SetCustomFields
so.topic: reference
---

# SetCustomFields(Map udefs)

Set the user-defined and extra fields on an NSDocumentEntity with a map.

## Parameters

* **udefs** Map user defined field and extra field values encoded as strings.

```crmscript
NSDocumentEntity thing;
Map udefs;
udefs["SuperOffice:1"] = "[I:123]";
udefs["SuperOffice:1"] = "123"; // this will also work, but beware of decimal point variations in different languages
udefs["custom.progid"] = "foobar";
udefs["x_foo"] = "foobar";
udefs["x_bar"] = "456"; // List item id
thing.SetCustomFields(udefs);
```
