---
uid: crmscript_ref_NSQuoteLine_GetDiscountPercent
title: Float GetDiscountPercent()
intellisense: NSQuoteLine.GetDiscountPercent
keywords: NSQuoteLine, GetDiscountPercent
so.topic: reference
---

# Float GetDiscountPercent()

The discount for the line, in percent. Both ‘DiscountPercent’ and ‘DiscountAmount’ shall be filled out, but the UserValueOverride field must be set to the field the user actually changed last. If this field is filled out by the user, it overrides any discount suggested by the connector. If the user has not filled this in, the system will copy the ERP discount amount to this field. The Percentage is given in integer form, i.e. ‘12%’ is represented as ‘12’.

**Returns:** Float

```crmscript
NSQuoteLine thing;
Float discountPercent  = thing.GetDiscountPercent();
```

