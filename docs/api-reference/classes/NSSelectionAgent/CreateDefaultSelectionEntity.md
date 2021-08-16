---
uid: crmscript_ref_NSSelectionAgent_CreateDefaultSelectionEntity
title: NSSelectionEntity CreateDefaultSelectionEntity()
intellisense: NSSelectionAgent.CreateDefaultSelectionEntity
keywords: NSSelectionAgent, CreateDefaultSelectionEntity
so.topic: reference
---

# NSSelectionEntity CreateDefaultSelectionEntity()
	  
Set default values into a new NSSelectionEntity.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** NSSelectionEntity

```crmscript
NSSelectionAgent agent;
NSSelectionEntity thing = agent.CreateDefaultSelectionEntity();
thing = agent.SaveSelectionEntity(thing);
```

