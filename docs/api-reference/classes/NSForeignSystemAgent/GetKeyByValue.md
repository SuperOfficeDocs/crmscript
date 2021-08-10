---
uid: crmscript_ref_NSForeignSystemAgent_GetKeyByValue
title: NSForeignKey GetKeyByValue(String applicationName, String deviceName, String keyName, String keyValue, String tableName)
intellisense: NSForeignSystemAgent.GetKeyByValue
keywords: NSForeignSystemAgent, GetKeyByValue
so.topic: reference
---

# NSForeignKey GetKeyByValue(String applicationName, String deviceName, String keyName, String keyValue, String tableName)

Get a foreignkey based on its name and value, that belongs to the specified device and application.

**Parameters:**
 - **applicationName** The name of the foreign application.
 - **deviceName** The name of the foreign device.
 - **keyName** The name of the foreign key.
 - **keyValue** Foreignkey value
 - **tableName** Table name, transformed to and from numeric table id by the service layer.<p/>Use an empty string to indicate that your key is not bound to any specific table.

**Returns:** NSForeignKey

```crmscript
NSForeignSystemAgent agent;
String applicationName;
String deviceName;
String keyName;
String keyValue;
String tableName;
NSForeignKey res = agent.GetKeyByValue(applicationName, deviceName, keyName, keyValue, tableName);
```

