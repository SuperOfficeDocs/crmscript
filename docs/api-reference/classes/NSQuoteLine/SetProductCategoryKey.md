---
uid: crmscript_ref_NSQuoteLine_SetProductCategoryKey
title: SetProductCategoryKey(String productCategoryKey)
intellisense: NSQuoteLine.SetProductCategoryKey
keywords: NSQuoteLine, GetProductCategoryKey
so.topic: reference
---

# SetProductCategoryKey(String productCategoryKey)

Either a List id to an id from a connector provided list, or, if the connection doesn't support lists, a text. Is stored here if the user changes the value from the product in the pricelist, or just enters a QuoteLine without a product link.

**Parameter:** 
 - **productCategoryKey** String

```crmscript
NSQuoteLine thing;
String productCategoryKey;
thing.SetProductCategoryKey(productCategoryKey);
```

