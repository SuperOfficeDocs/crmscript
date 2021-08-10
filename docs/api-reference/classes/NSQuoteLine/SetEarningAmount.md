---
uid: crmscript_ref_NSQuoteLine_SetEarningAmount
title: SetEarningAmount(Float earningAmount)
intellisense: NSQuoteLine.SetEarningAmount
keywords: NSQuoteLine, GetEarningAmount
so.topic: reference
---

# SetEarningAmount(Float earningAmount)

The earning, in whatever currency the sale is in. Both ‘EarningAmount and ‘EarningPercent shall be filled out, but the UserValueOverride field must be set to the field the user actually changed last.

**Parameter:** 
 - **earningAmount** Float

```crmscript
NSQuoteLine thing;
Float earningAmount;
thing.SetEarningAmount(earningAmount);
```

