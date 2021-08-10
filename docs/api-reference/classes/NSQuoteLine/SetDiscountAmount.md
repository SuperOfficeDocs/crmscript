---
uid: crmscript_ref_NSQuoteLine_SetDiscountAmount
title: SetDiscountAmount(Float discountAmount)
intellisense: NSQuoteLine.SetDiscountAmount
keywords: NSQuoteLine, GetDiscountAmount
so.topic: reference
---

# SetDiscountAmount(Float discountAmount)

The discount for the line, in whatever currency the sale is in. Both ‘DiscountPercent’ and ‘DiscountAmount’ shall be filled out, but the UserValueOverride field must be set to the field the user actually changed last. If this field is filled out by the user, it overrides any discount suggested by the connector. If the user has not filled this in, the system will copy the ERP discount amount to this field.

**Parameter:** 
 - **discountAmount** Float

```crmscript
NSQuoteLine thing;
Float discountAmount;
thing.SetDiscountAmount(discountAmount);
```

