---
uid: crmscript_ref_NSQuoteLine_GetTotalPrice
title: Float GetTotalPrice()
intellisense: NSQuoteLine.GetTotalPrice
keywords: NSQuoteLine, GetTotalPrice
so.topic: reference
---

# Float GetTotalPrice()

TotalPrice  = SubTotal - DiscountAmount or TotalPrice = (UnitCost * Quantity) + EarningAmount, according to what the user changed last.

**Returns:** Float

```crmscript
NSQuoteLine thing;
Float totalPrice  = thing.GetTotalPrice();
```

