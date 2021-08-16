---
uid: crmscript_ref_NSPriceList_GetValidTo
title: DateTime GetValidTo()
intellisense: NSPriceList.GetValidTo
keywords: NSPriceList, GetValidTo
so.topic: reference
---

# DateTime GetValidTo()

The date (inclusive) the pricelist ends to be valid. This can be DateTime.MaxValue to signal that it doesn't have a specific end date.

**Returns:** DateTime

```crmscript
NSPriceList thing;
DateTime validTo  = thing.GetValidTo();
```

