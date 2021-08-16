---
uid: crmscript_ref_NSArchiveAgent_GetArchiveConfiguration
title: NSArchiveConfiguration GetArchiveConfiguration(String guiName, String providerName)
intellisense: NSArchiveAgent.GetArchiveConfiguration
keywords: NSArchiveAgent, GetArchiveConfiguration
so.topic: reference
---

# NSArchiveConfiguration GetArchiveConfiguration(String guiName, String providerName)

Get the configuration for one archive. The configuration is keyed by a combination of archive provider name and gui name. The archive provider name must match an archive provider plugin; the gui name is an arbitrary string used to distinguish multiple occurrences of the same underlying provider in a gui.

**Parameters:**
 - **guiName** String that identifies the archive in the GUI, must be the same when fetching and storing configurations, but does not otherwise have to match anything.
 - **providerName** Name of archive provider, must match one of the plugins known to the ArchiveProviderFactory.

**Returns:** Archive configuration consisting of column information, orderby information and entities

```crmscript
NSArchiveAgent agent;
String guiName;
String providerName;
NSArchiveConfiguration res = agent.GetArchiveConfiguration(guiName, providerName);
```

