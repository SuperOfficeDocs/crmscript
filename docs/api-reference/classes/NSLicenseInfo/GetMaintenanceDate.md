---
uid: crmscript_ref_NSLicenseInfo_GetMaintenanceDate
title: DateTime GetMaintenanceDate()
intellisense: NSLicenseInfo.GetMaintenanceDate
keywords: NSLicenseInfo, GetMaintenanceDate
so.topic: reference
---

# DateTime GetMaintenanceDate()

Expiration date for maintenance. After this date, upgrades should refuse to install.

**Returns:** DateTime

```crmscript
NSLicenseInfo thing;
DateTime maintenanceDate  = thing.GetMaintenanceDate();
```

