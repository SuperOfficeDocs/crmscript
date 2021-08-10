---
uid: crmscript_ref_NSMarketingAgent_SaveFormEntity
title: NSFormEntity SaveFormEntity(NSFormEntity formEntity);
intellisense: NSMarketingAgent.SaveFormEntity
keywords: NSMarketingAgent, SaveFormEntity
so.topic: reference
---

# NSFormEntity SaveFormEntity(NSFormEntity formEntity);
	  
Updates the existing NSFormEntity or creates a new NSFormEntity if the id parameter is 0
	  
**Parameters**:
 - **formEntity** The NSFormEntity to save.

**Returns:** NSFormEntity

```crmscript
NSMarketing  agent;
NSFormEntity thing = agent.CreateDefaultFormEntity();
thing = agent.SaveFormEntity(thing);
```

