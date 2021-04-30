﻿---
uid: crmscript_ref_NSNumberAllocationAgent_SaveRefCountEntity
title: NSRefCountEntity SaveRefCountEntity(NSRefCountEntity refCountEntity);
intellisense: NSNumberAllocationAgent.SaveRefCountEntity
keywords: NSNumberAllocationAgent, SaveRefCountEntity
so.topic: reference
---
	  
Updates the existing NSRefCountEntity or creates a new NSRefCountEntity if the id parameter is 0
	  
**Parameters**:
 - **refCountEntity** The NSRefCountEntity to save.

**Returns:** New or updated NSRefCountEntity

```crmscript
NSNumberAllocation  agent;
NSRefCountEntity thing = agent.CreateDefaultRefCountEntity();
thing = agent.SaveRefCountEntity(thing);
```
