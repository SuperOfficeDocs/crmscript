﻿---
uid: crmscript_ref_NSChatAgent_SaveChatSessionEntity
title: NSChatSessionEntity SaveChatSessionEntity(NSChatSessionEntity chatSessionEntity);
intellisense: NSChatAgent.SaveChatSessionEntity
keywords: NSChatAgent, SaveChatSessionEntity
so.topic: reference
---
	  
Updates the existing NSChatSessionEntity or creates a new NSChatSessionEntity if the id parameter is 0
	  
**Parameters**:
 - **chatSessionEntity** The NSChatSessionEntity to save.

**Returns:** NSChatSessionEntity

```crmscript
NSChat  agent;
NSChatSessionEntity thing = agent.CreateDefaultChatSessionEntity();
thing = agent.SaveChatSessionEntity(thing);
```

