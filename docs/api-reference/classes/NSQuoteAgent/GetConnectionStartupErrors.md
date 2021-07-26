---
uid: crmscript_ref_NSQuoteAgent_GetConnectionStartupErrors
title: NSPluginResponse[] GetConnectionStartupErrors()
intellisense: NSQuoteAgent.GetConnectionStartupErrors
keywords: NSQuoteAgent, GetConnectionStartupErrors
so.topic: reference
---

Returns an array of PluginResponseInfos for all failed connection initializations.


**Returns:** Array of PluginResponseInfos for each failed connection initialization.

```crmscript
NSQuoteAgent agent;
NSPluginResponse[] res = agent.GetConnectionStartupErrors();
```

