---
uid: crmscript_ref_NSQuoteLine_SetSupplier
title: SetSupplier(String supplier)
intellisense: NSQuoteLine.SetSupplier
keywords: NSQuoteLine, GetSupplier
so.topic: reference
---

# SetSupplier(String supplier)

The name of the supplier. Is stored here if the user changes the value from the product in the pricelist, or just enters a QuoteLine without a product link.

**Parameter:** 
 - **supplier** String

```crmscript
NSQuoteLine thing;
String supplier;
thing.SetSupplier(supplier);
```

