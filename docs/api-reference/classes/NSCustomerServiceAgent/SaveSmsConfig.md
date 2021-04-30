﻿---
uid: crmscript_ref_NSCustomerServiceAgent_SaveSmsConfig
title: NSSmsConfig SaveSmsConfig(NSSmsConfig smsConfig);
intellisense: NSCustomerServiceAgent.SaveSmsConfig
keywords: NSCustomerServiceAgent, SaveSmsConfig
so.topic: reference
---
	  
Updates the existing NSSmsConfig or creates a new NSSmsConfig if the id parameter is 0
	  
**Parameters**:
 - **smsConfig** The NSSmsConfig to save.

**Returns:** New or updated NSSmsConfig

```crmscript
NSCustomerService  agent;
NSSmsConfig thing = agent.CreateDefaultSmsConfig();
thing = agent.SaveSmsConfig(thing);
```
