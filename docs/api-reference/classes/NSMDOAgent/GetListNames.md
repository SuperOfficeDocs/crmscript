﻿---
uid: crmscript_ref_NSMDOAgent_GetListNames
title: StringArray GetListNames()
intellisense: NSMDOAgent.GetListNames
keywords: NSMDOAgent, GetListNames
so.topic: reference
---

Returns a list of all MDO List names. These names can also be used with the Archive agent as ProviderNames.


**Returns:** Array of list names.

```crmscript
NSMDOAgent agent;
StringArray res = agent.GetListNames();
```
