---
uid: crmscript_ref_NSListAgent_CreateDefaultTicketStatusEntity
title: NSTicketStatusEntity CreateDefaultTicketStatusEntity()
intellisense: NSListAgent.CreateDefaultTicketStatusEntity
keywords: NSListAgent, CreateDefaultTicketStatusEntity
so.topic: reference
---

# NSTicketStatusEntity CreateDefaultTicketStatusEntity()
	  
Set default values into a new NSTicketStatusEntity.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** NSTicketStatusEntity

```crmscript
NSListAgent agent;
NSTicketStatusEntity thing = agent.CreateDefaultTicketStatusEntity();
thing = agent.SaveTicketStatusEntity(thing);
```

