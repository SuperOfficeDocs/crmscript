﻿---
uid: crmscript_ref_NSListAgent_GetAllCountries
title: Country[] GetAllCountries(Bool includeDeleted)
intellisense: NSListAgent.GetAllCountries
keywords: NSListAgent, GetAllCountries
so.topic: reference
---

Returns all available countries a contact or person could belong to.

**Parameters:**
 - **includeDeleted** Include deleted items in result?

**Returns:** An array of all available countries

```crmscript
NSListAgent agent;
Bool includeDeleted;
Country[] res = agent.GetAllCountries(includeDeleted);
```

