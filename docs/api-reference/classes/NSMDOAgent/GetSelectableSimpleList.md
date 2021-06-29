﻿---
uid: crmscript_ref_NSMDOAgent_GetSelectableSimpleList
title: SelectableMDOListItem[] GetSelectableSimpleList(String name)
intellisense: NSMDOAgent.GetSelectableSimpleList
keywords: NSMDOAgent, GetSelectableSimpleList
so.topic: reference
---

Method returns a flat Selectable MDO List.

**Parameters:**
 - **name** Conceptual name of the MDO list

**Returns:** Array of SelectableMDOListItem

```crmscript
NSMDOAgent agent;
String name;
SelectableMDOListItem[] res = agent.GetSelectableSimpleList(name);
```

