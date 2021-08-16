---
uid: crmscript_ref_NSQuoteEntity_GetActiveQuoteVersionId
title: Integer GetActiveQuoteVersionId()
intellisense: NSQuoteEntity.GetActiveQuoteVersionId
keywords: NSQuoteEntity, GetActiveQuoteVersionId
so.topic: reference
---

# Integer GetActiveQuoteVersionId()

The primary key of the Quote Version that is currently active. (The active version will always be the latest version.)

**Returns:** Integer

```crmscript
NSQuoteEntity thing;
Integer activeQuoteVersionId  = thing.GetActiveQuoteVersionId();
```

