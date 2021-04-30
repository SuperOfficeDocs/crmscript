﻿---
uid: crmscript_ref_NSMDOAgent_SetSelected
title: SelectableMDOListItemArray SetSelected(String name, String additionalInfo, SelectableMDOListItemArray selectableMDOList)
intellisense: NSMDOAgent.SetSelected
keywords: NSMDOAgent, SetSelected
so.topic: reference
---

Saves the selected values as selected by their given list representation.

**Parameters:**
 - **name** Conceptual name of the MDO list
 - **additionalInfo** Additional info to the MDO provider
 - **selectableMDOList** Items to be updated

**Returns:** Array of updated SelectableMDOListItems

```crmscript
NSMDOAgent agent;
String name;
String additionalInfo;
SelectableMDOListItemArray selectableMDOList;
SelectableMDOListItemArray res = agent.SetSelected(name, additionalInfo, selectableMDOList);
```
