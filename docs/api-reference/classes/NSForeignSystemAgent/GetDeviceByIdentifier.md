﻿---
uid: crmscript_ref_NSForeignSystemAgent_GetDeviceByIdentifier
title: NSForeignDevice GetDeviceByIdentifier(String applicationName, String deviceName, String deviceIdentifier)
intellisense: NSForeignSystemAgent.GetDeviceByIdentifier
keywords: NSForeignSystemAgent, GetDeviceByIdentifier
so.topic: reference
---

Gets a NSForeignDevice with deviceName and deviceIdentifier that belongs to the application with applicationName.

**Parameters:**
 - **applicationName** The name of the foreign application.
 - **deviceName** The name of the foreign device.
 - **deviceIdentifier** Optional unique id of device (Palm pilot device ID, version number, etc)

**Returns:** NSForeignDevice

```crmscript
NSForeignSystemAgent agent;
String applicationName;
String deviceName;
String deviceIdentifier;
NSForeignDevice res = agent.GetDeviceByIdentifier(applicationName, deviceName, deviceIdentifier);
```

