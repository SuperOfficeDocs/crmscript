---
uid: crmscript_ref_NSDocumentEntity_GetExtraFields
title: Map GetExtraFields()
intellisense: NSDocumentEntity.GetExtraFields
keywords: NSDocumentEntity, GetExtraFields
so.topic: reference
---

# Map GetExtraFields()

Get the extra fields on NSDocumentEntity as a map.

**Returns:** Map

```crmscript
NSDocumentEntity thing;
Map extras = thing.GetExtraFields();
log( extras["x_abc"] ); // "[I:123]" - integer or list item id
log( extras["x_abc:DisplayText"] ); // "bla bla" - list item value
log( extras["x_bla"] ); // "foobar" - string value
```

