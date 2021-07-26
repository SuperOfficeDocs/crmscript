﻿---
uid: crmscript_ref_NSConfigurationAgent_ExistsSystemEvent
title: Bool ExistsSystemEvent(String key)
intellisense: NSConfigurationAgent.ExistsSystemEvent
keywords: NSConfigurationAgent, ExistsSystemEvent
so.topic: reference
---

Is there a system event with the given key?

**Parameters:**
 - **key** The key to match on

**Returns:** Bool

```crmscript
NSConfigurationAgent agent;
String key;
Bool res = agent.ExistsSystemEvent(key);
```

