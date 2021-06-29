﻿---
uid: crmscript_ref_NSListAgent_GetAllTicketPriorities
title: TicketPriorityEntity[] GetAllTicketPriorities(Bool includeDeleted)
intellisense: NSListAgent.GetAllTicketPriorities
keywords: NSListAgent, GetAllTicketPriorities
so.topic: reference
---

Returns all available ticket priorities.

**Parameters:**
 - **includeDeleted** Include deleted items in result?

**Returns:** An array of all available ticket priorities

```crmscript
NSListAgent agent;
Bool includeDeleted;
TicketPriorityEntity[] res = agent.GetAllTicketPriorities(includeDeleted);
```

