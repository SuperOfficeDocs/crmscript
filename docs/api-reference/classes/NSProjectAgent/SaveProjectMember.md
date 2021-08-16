---
uid: crmscript_ref_NSProjectAgent_SaveProjectMember
title: NSProjectMember SaveProjectMember(NSProjectMember projectMember);
intellisense: NSProjectAgent.SaveProjectMember
keywords: NSProjectAgent, SaveProjectMember
so.topic: reference
---

# NSProjectMember SaveProjectMember(NSProjectMember projectMember);
	  
Updates the existing NSProjectMember or creates a new NSProjectMember if the id parameter is 0
	  
**Parameters**:
 - **projectMember** The NSProjectMember to save.

**Returns:** NSProjectMember

```crmscript
NSProject  agent;
NSProjectMember thing = agent.CreateDefaultProjectMember();
thing = agent.SaveProjectMember(thing);
```

