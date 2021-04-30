﻿---
uid: crmscript_ref_NSQuoteAgent_DeleteConnection
title: Void DeleteConnection(Integer quoteConnectionId)
intellisense: NSQuoteAgent.DeleteConnection
keywords: NSQuoteAgent, DeleteConnection
so.topic: reference
---

Marks a connection as deleted.

**Parameters:**
 - **quoteConnectionId** Primary key of the connection to delete

**Returns:** A void return

```crmscript
NSQuoteAgent agent;
Integer quoteConnectionId;
Void res = agent.DeleteConnection(quoteConnectionId);
```
