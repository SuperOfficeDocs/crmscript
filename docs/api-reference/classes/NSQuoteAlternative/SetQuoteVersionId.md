---
uid: crmscript_ref_NSQuoteAlternative_SetQuoteVersionId
title: SetQuoteVersionId(Integer quoteVersionId)
intellisense: NSQuoteAlternative.SetQuoteVersionId
keywords: NSQuoteAlternative, GetQuoteVersionId
so.topic: reference
---

# SetQuoteVersionId(Integer quoteVersionId)

The version that owns this alternative (the chain is Sale 1->1 Quote 1->+ QuoteVersion 1->+ QuoteAlternative.

**Parameter:** 
 - **quoteVersionId** Integer

```crmscript
NSQuoteAlternative thing;
Integer quoteVersionId;
thing.SetQuoteVersionId(quoteVersionId);
```

