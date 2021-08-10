---
uid: crmscript_ref_NSQuoteLine_SetProductTypeKey
title: SetProductTypeKey(String productTypeKey)
intellisense: NSQuoteLine.SetProductTypeKey
keywords: NSQuoteLine, GetProductTypeKey
so.topic: reference
---

# SetProductTypeKey(String productTypeKey)

Either a List id to an id from a connector provided list, or, if the connection doesn't support lists, a text. Is stored here if the user changes the value from the product in the pricelist, or just enters a QuoteLine without a product link.

**Parameter:** 
 - **productTypeKey** String

```crmscript
NSQuoteLine thing;
String productTypeKey;
thing.SetProductTypeKey(productTypeKey);
```

