﻿---
uid: crmscript_ref_NSSaleAgent_GetSalesFromPerson
title: Sale[] GetSalesFromPerson(Integer personId, Bool onlyOpenSales)
intellisense: NSSaleAgent.GetSalesFromPerson
keywords: NSSaleAgent, GetSalesFromPerson
so.topic: reference
---

Returns all sales for the person provided.

**Parameters:**
 - **personId** The ID of the person whose sales we want.
 - **onlyOpenSales** If true, only get open sales.

**Returns:** List of sales matching query

```crmscript
NSSaleAgent agent;
Integer personId;
Bool onlyOpenSales;
Sale[] res = agent.GetSalesFromPerson(personId, onlyOpenSales);
```

