---
uid: crmscript_ref_NSQuoteAlternative_SetVATInfo
title: SetVATInfo(String vATInfo)
intellisense: NSQuoteAlternative.SetVATInfo
keywords: NSQuoteAlternative, GetVATInfo
so.topic: reference
---

# SetVATInfo(String vATInfo)

Extra info about VAT that the connector might insert. This field has no business logic in the CRM code, but is available as a merge field in the quote documents.

**Parameter:** 
 - **vATInfo** String

```crmscript
NSQuoteAlternative thing;
String vATInfo;
thing.SetVATInfo(vATInfo);
```

