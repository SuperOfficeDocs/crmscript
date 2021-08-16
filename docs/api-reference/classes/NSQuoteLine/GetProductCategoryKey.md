---
uid: crmscript_ref_NSQuoteLine_GetProductCategoryKey
title: String GetProductCategoryKey()
intellisense: NSQuoteLine.GetProductCategoryKey
keywords: NSQuoteLine, GetProductCategoryKey
so.topic: reference
---

# String GetProductCategoryKey()

Either a List id to an id from a connector provided list, or, if the connection doesn't support lists, a text. Is stored here if the user changes the value from the product in the pricelist, or just enters a QuoteLine without a product link.

**Returns:** String

```crmscript
NSQuoteLine thing;
String productCategoryKey  = thing.GetProductCategoryKey();
```

