---
uid: crmscript_ref_NSQuoteAlternative_GetVAT
title: Float GetVAT()
intellisense: NSQuoteAlternative.GetVAT
keywords: NSQuoteAlternative, GetVAT
so.topic: reference
---

# Float GetVAT()

Tax/VAT - THIS IS AN AMOUNT, available as a merge field in the quote document. The SuperOffice quote connector will calculate this field based on the vat PERCENTAGES on the individual lines; other connectors may implement other algorithms at will.

**Returns:** Float

```crmscript
NSQuoteAlternative thing;
Float vAT  = thing.GetVAT();
```

