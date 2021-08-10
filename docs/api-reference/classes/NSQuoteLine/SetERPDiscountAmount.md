---
uid: crmscript_ref_NSQuoteLine_SetERPDiscountAmount
title: SetERPDiscountAmount(Float eRPDiscountAmount)
intellisense: NSQuoteLine.SetERPDiscountAmount
keywords: NSQuoteLine, GetERPDiscountAmount
so.topic: reference
---

# SetERPDiscountAmount(Float eRPDiscountAmount)

The discount the system calculates based on customer / quantity / whatever. Can be overrided by the salesman in the field 'DiscountPercent' or 'DiscountAmount'. If UserValueOverride is set to ‘None’ then the value is copied to DiscountAmount. Both fields ERPDiscountPercent and ERPDiscountAmount will be filled out.

**Parameter:** 
 - **eRPDiscountAmount** Float

```crmscript
NSQuoteLine thing;
Float eRPDiscountAmount;
thing.SetERPDiscountAmount(eRPDiscountAmount);
```

