﻿---
uid: crmscript_ref_NSEMailAgent_CreateDefaultEMailSOInfo
title: NSEMailSOInfo CreateDefaultEMailSOInfo()
intellisense: NSEMailAgent.CreateDefaultEMailSOInfo
keywords: NSEMailAgent, CreateDefaultEMailSOInfo
so.topic: reference
---
	  
Set default values into a new NSEMailSOInfo.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** NSEMailSOInfo

```crmscript
NSEMailAgent agent;
NSEMailSOInfo thing = agent.CreateDefaultEMailSOInfo();
thing = agent.SaveEMailSOInfo(thing);
```

