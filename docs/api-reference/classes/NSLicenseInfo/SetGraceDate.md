---
uid: crmscript_ref_NSLicenseInfo_SetGraceDate
title: SetGraceDate(DateTime graceDate)
intellisense: NSLicenseInfo.SetGraceDate
keywords: NSLicenseInfo, GetGraceDate
so.topic: reference
---

# SetGraceDate(DateTime graceDate)

Real expiration date, when the given module actually stops working. Modules that normally update data should switch to read-only mode. Modules that only read anyway, should disable themselves in some other way

**Parameter:** 
 - **graceDate** DateTime

```crmscript
NSLicenseInfo thing;
DateTime graceDate;
thing.SetGraceDate(graceDate);
```

