﻿---
uid: crmscript_ref_NSListAgent_DeleteFromListName
title: Void DeleteFromListName(Integer id, String udListDefinitionName)
intellisense: NSListAgent.DeleteFromListName
keywords: NSListAgent, DeleteFromListName
so.topic: reference
---

Delete a list item from the specified list defintion

**Parameters:**
 - **id** The identity of the list item to delete
 - **udListDefinitionName** The name of the list definition, indicating which list to delete the items from.

```crmscript
NSListAgent agent;
Integer id;
String udListDefinitionName;
agent.DeleteFromListName(id, udListDefinitionName);
```

