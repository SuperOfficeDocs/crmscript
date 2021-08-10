---
uid: crmscript_ref_NSConfigurationAgent_SaveSystemEventEntity
title: NSSystemEventEntity SaveSystemEventEntity(NSSystemEventEntity systemEventEntity);
intellisense: NSConfigurationAgent.SaveSystemEventEntity
keywords: NSConfigurationAgent, SaveSystemEventEntity
so.topic: reference
---

# NSSystemEventEntity SaveSystemEventEntity(NSSystemEventEntity systemEventEntity);
	  
Updates the existing NSSystemEventEntity or creates a new NSSystemEventEntity if the id parameter is 0
	  
**Parameters**:
 - **systemEventEntity** The NSSystemEventEntity to save.

**Returns:** NSSystemEventEntity

```crmscript
NSConfiguration  agent;
NSSystemEventEntity thing = agent.CreateDefaultSystemEventEntity();
thing = agent.SaveSystemEventEntity(thing);
```

