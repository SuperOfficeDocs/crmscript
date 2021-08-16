---
uid: crmscript_ref_NSQuote_GetERPQuoteKey
title: String GetERPQuoteKey()
intellisense: NSQuote.GetERPQuoteKey
keywords: NSQuote, GetERPQuoteKey
so.topic: reference
---

# String GetERPQuoteKey()

Foreign key of quote (if available). The key in the ERP system that identifies this sale's Quote (as opposed to the later Order information)

**Returns:** String

```crmscript
NSQuote thing;
String eRPQuoteKey  = thing.GetERPQuoteKey();
```

