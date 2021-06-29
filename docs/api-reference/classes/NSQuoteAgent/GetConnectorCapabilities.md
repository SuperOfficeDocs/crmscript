﻿---
uid: crmscript_ref_NSQuoteAgent_GetConnectorCapabilities
title: String[] GetConnectorCapabilities(Integer quoteConnectionId)
intellisense: NSQuoteAgent.GetConnectorCapabilities
keywords: NSQuoteAgent, GetConnectorCapabilities
so.topic: reference
---

Gets a list of connector capabilities

**Parameters:**
 - **quoteConnectionId** Primary key of the connection

**Returns:** Capabilities

```crmscript
NSQuoteAgent agent;
Integer quoteConnectionId;
String[] res = agent.GetConnectorCapabilities(quoteConnectionId);
```

