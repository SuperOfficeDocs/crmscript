---
uid: crmscript_ref_NSQuoteConnection_GetDeleted
title: Bool GetDeleted()
intellisense: NSQuoteConnection.GetDeleted
keywords: NSQuoteConnection, GetDeleted
so.topic: reference
---

# Bool GetDeleted()

If set, then this is a row that has been 'deleted'; we do not physically delete rows to avoid disaster.

**Returns:** Bool

```crmscript
NSQuoteConnection thing;
Bool deleted  = thing.GetDeleted();
```

