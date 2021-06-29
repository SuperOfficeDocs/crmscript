﻿---
uid: crmscript_ref_NSListAgent_GetAllFromListName
title: ListItemEntity[] GetAllFromListName(String udListDefinitionName, Bool includeDeleted)
intellisense: NSListAgent.GetAllFromListName
keywords: NSListAgent, GetAllFromListName
so.topic: reference
---

Get all list items for the specified list defintion

**Parameters:**
 - **udListDefinitionName** The name of the list definition, indicating which list to get the item from.
 - **includeDeleted** Include deleted items in result?

**Returns:** The list items

```crmscript
NSListAgent agent;
String udListDefinitionName;
Bool includeDeleted;
ListItemEntity[] res = agent.GetAllFromListName(udListDefinitionName, includeDeleted);
```

