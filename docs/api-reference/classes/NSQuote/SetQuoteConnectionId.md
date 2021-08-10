---
uid: crmscript_ref_NSQuote_SetQuoteConnectionId
title: SetQuoteConnectionId(Integer quoteConnectionId)
intellisense: NSQuote.SetQuoteConnectionId
keywords: NSQuote, GetQuoteConnectionId
so.topic: reference
---

# SetQuoteConnectionId(Integer quoteConnectionId)

The connection in the CRM system to where this quote came from. Identifies the ERP connection used for this quote. Each quote is bound to one and only one connection.

**Parameter:** 
 - **quoteConnectionId** Integer

```crmscript
NSQuote thing;
Integer quoteConnectionId;
thing.SetQuoteConnectionId(quoteConnectionId);
```

