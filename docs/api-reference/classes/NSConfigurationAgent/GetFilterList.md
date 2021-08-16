---
uid: crmscript_ref_NSConfigurationAgent_GetFilterList
title: String GetFilterList(String application, String instance)
intellisense: NSConfigurationAgent.GetFilterList
keywords: NSConfigurationAgent, GetFilterList
so.topic: reference
---

# String GetFilterList(String application, String instance)

Get the list of filters to be used for processing the configuration data for this application.

**Parameters:**
 - **application** The application name, for instance 'SixWeb'
 - **instance** The instance name for the application, like 'MainInstance'

**Returns:** String

```crmscript
NSConfigurationAgent agent;
String application;
String instance;
String res = agent.GetFilterList(application, instance);
```

