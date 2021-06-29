﻿---
uid: crmscript_ref_NSUserDefinedFieldInfoAgent_GetUserDefinedFieldFromIds
title: UserDefinedFieldInfo[] GetUserDefinedFieldFromIds(Integer[]ids)
intellisense: NSUserDefinedFieldInfoAgent.GetUserDefinedFieldFromIds
keywords: NSUserDefinedFieldInfoAgent, GetUserDefinedFieldFromIds
so.topic: reference
---

Return an given array of user defined field identified by the ids.

**Parameters:**
 - **ids** Array of user defined field ids

**Returns:** Returns an array of user-defined field info carriers

```crmscript
NSUserDefinedFieldInfoAgent agent;
Integer[]ids;
UserDefinedFieldInfo[] res = agent.GetUserDefinedFieldFromIds(ids);
```

