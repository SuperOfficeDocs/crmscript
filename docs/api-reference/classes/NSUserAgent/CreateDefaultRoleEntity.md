---
uid: crmscript_ref_NSUserAgent_CreateDefaultRoleEntity
title: NSRoleEntity CreateDefaultRoleEntity()
intellisense: NSUserAgent.CreateDefaultRoleEntity
keywords: NSUserAgent, CreateDefaultRoleEntity
so.topic: reference
---

# NSRoleEntity CreateDefaultRoleEntity()
	  
Set default values into a new NSRoleEntity.
NetServer calculates default values (e.g. Country) on the entity, which is required when creating/storing a new instance
	  
**Returns:** NSRoleEntity

```crmscript
NSUserAgent agent;
NSRoleEntity thing = agent.CreateDefaultRoleEntity();
thing = agent.SaveRoleEntity(thing);
```

