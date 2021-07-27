﻿---
uid: crmscript_ref_NSListAgent_SaveHierarchyEntity
title: NSHierarchyEntity SaveHierarchyEntity(NSHierarchyEntity hierarchyEntity);
intellisense: NSListAgent.SaveHierarchyEntity
keywords: NSListAgent, SaveHierarchyEntity
so.topic: reference
---
	  
Updates the existing NSHierarchyEntity or creates a new NSHierarchyEntity if the id parameter is 0
	  
**Parameters**:
 - **hierarchyEntity** The NSHierarchyEntity to save.

**Returns:** NSHierarchyEntity

```crmscript
NSList  agent;
NSHierarchyEntity thing = agent.CreateDefaultHierarchyEntity();
thing = agent.SaveHierarchyEntity(thing);
```

