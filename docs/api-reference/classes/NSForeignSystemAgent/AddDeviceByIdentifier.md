﻿---
uid: crmscript_ref_NSForeignSystemAgent_AddDeviceByIdentifier
title: NSForeignDevice AddDeviceByIdentifier(String applicationName, String deviceName, String deviceIdentifier)
intellisense: NSForeignSystemAgent.AddDeviceByIdentifier
keywords: NSForeignSystemAgent, AddDeviceByIdentifier
so.topic: reference
---

Adds a new NSForeignDevice with deviceName that belongs to the application with applicationName, with an optional device-specific identifier.

**Parameters:**
 - **applicationName** The name of the foreign application.
 - **deviceName** The name of the foreign device.
 - **deviceIdentifier** Unique id of device (Palm pilot device ID, version number, etc)

**Returns:** NSForeignDevice.

```crmscript
NSForeignSystemAgent agent;
String applicationName;
String deviceName;
String deviceIdentifier;
NSForeignDevice res = agent.AddDeviceByIdentifier(applicationName, deviceName, deviceIdentifier);
```

