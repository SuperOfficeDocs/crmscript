---
uid: crmscript_ref_NSQuoteVersion_GetLastRecalculated
title: DateTime GetLastRecalculated()
intellisense: NSQuoteVersion.GetLastRecalculated
keywords: NSQuoteVersion, GetLastRecalculated
so.topic: reference
---

# DateTime GetLastRecalculated()

When this version was last subjected to a total recalculation. This field must be set by the connector, since the connector may choose to ignore a RecalculateVersion call based on policies and possibly the current value of this field. SuperOffice will set this field to 1.1.1760 whenever any change occurs to the quote, to indicate that a recalculation is needed.

**Returns:** DateTime

```crmscript
NSQuoteVersion thing;
DateTime lastRecalculated  = thing.GetLastRecalculated();
```

