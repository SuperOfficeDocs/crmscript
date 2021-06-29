﻿---
uid: crmscript_ref_NSListAgent_GetHeadingsFromName
title: HeadingEntity[] GetHeadingsFromName(String name)
intellisense: NSListAgent.GetHeadingsFromName
keywords: NSListAgent, GetHeadingsFromName
so.topic: reference
---

Gets headings for list resolved by the provided name.

**Parameters:**
 - **name** The name of the list to look up.

**Returns:** List of headings

```crmscript
NSListAgent agent;
String name;
HeadingEntity[] res = agent.GetHeadingsFromName(name);
```

