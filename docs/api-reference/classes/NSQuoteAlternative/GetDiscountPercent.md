---
uid: crmscript_ref_NSQuoteAlternative_GetDiscountPercent
title: Float GetDiscountPercent()
intellisense: NSQuoteAlternative.GetDiscountPercent
keywords: NSQuoteAlternative, GetDiscountPercent
so.topic: reference
---

# Float GetDiscountPercent()

The discount the sales rep specifies, in percent. Both the two ‘DiscountPercent’ and ‘DiscountAmount’ shall be filled out, but the UserValueOverride field must be set to the field the user actually changed. If this field is filled out by the user, it overrides the discount suggested by the connector. If the user has not filled any values, the system will copy the ERP discount percent value into this field. The Percentage is given in integer form, i.e. ‘12%’ is represented as ‘12’.

**Returns:** Float

```crmscript
NSQuoteAlternative thing;
Float discountPercent  = thing.GetDiscountPercent();
```

