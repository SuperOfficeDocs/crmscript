﻿---
uid: crmscript_ref_NSUserAgent_GetAllUserGroups
title: UserGroup[] GetAllUserGroups(Bool includeDeleted)
intellisense: NSUserAgent.GetAllUserGroups
keywords: NSUserAgent, GetAllUserGroups
so.topic: reference
---

Get all user groups

**Parameters:**
 - **includeDeleted** Include user groups with Deleted set to true

**Returns:** All user groups

```crmscript
NSUserAgent agent;
Bool includeDeleted;
UserGroup[] res = agent.GetAllUserGroups(includeDeleted);
```

