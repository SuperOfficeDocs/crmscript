---
uid: crmscript_ref_NSQuoteLine_SetUnitMinimumPrice
title: SetUnitMinimumPrice(Float unitMinimumPrice)
intellisense: NSQuoteLine.SetUnitMinimumPrice
keywords: NSQuoteLine, GetUnitMinimumPrice
so.topic: reference
---

# SetUnitMinimumPrice(Float unitMinimumPrice)

The minimum price this line can be sold for (to limit discounting). Will come from the connector. List price per unit must exceed the minimum price per unit.

**Parameter:** 
 - **unitMinimumPrice** Float

```crmscript
NSQuoteLine thing;
Float unitMinimumPrice;
thing.SetUnitMinimumPrice(unitMinimumPrice);
```

