﻿---
uid: crmscript_ref_NSDocumentAgent_GetSaleDocuments
title: Document[] GetSaleDocuments(Integer saleId)
intellisense: NSDocumentAgent.GetSaleDocuments
keywords: NSDocumentAgent, GetSaleDocuments
so.topic: reference
---

Get all documents that are linked to the sale. I.e. the documents that are listed in the sale dialog.

**Parameters:**
 - **saleId** The sale id.

**Returns:** Array of documents

```crmscript
NSDocumentAgent agent;
Integer saleId;
Document[] res = agent.GetSaleDocuments(saleId);
```

