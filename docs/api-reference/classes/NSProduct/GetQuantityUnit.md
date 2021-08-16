---
uid: crmscript_ref_NSProduct_GetQuantityUnit
title: String GetQuantityUnit()
intellisense: NSProduct.GetQuantityUnit
keywords: NSProduct, GetQuantityUnit
so.topic: reference
---

# String GetQuantityUnit()

What is the unit (meter, ton, bushel, microsecond, gradus, τρυβλίον, 五合枡, دونم or whatever); Connector handles conversion relative to PriceUnit if they are different

**Returns:** String

```crmscript
NSProduct thing;
String quantityUnit  = thing.GetQuantityUnit();
```

