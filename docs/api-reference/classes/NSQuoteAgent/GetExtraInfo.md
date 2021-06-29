﻿---
uid: crmscript_ref_NSQuoteAgent_GetExtraInfo
title: ProductExtraDataField[] GetExtraInfo(String quoteLineExtraData)
intellisense: NSQuoteAgent.GetExtraInfo
keywords: NSQuoteAgent, GetExtraInfo
so.topic: reference
---

Converts an xml string into an object representation.

**Parameters:**
 - **quoteLineExtraData** The extra data as xml.

**Returns:** An object representation on the xml

```crmscript
NSQuoteAgent agent;
String quoteLineExtraData;
ProductExtraDataField[] res = agent.GetExtraInfo(quoteLineExtraData);
```

