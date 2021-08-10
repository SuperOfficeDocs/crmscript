---
uid: crmscript_ref_NSPocketDeviceInfo_SetPlatform
title: SetPlatform(Integer platform)
intellisense: NSPocketDeviceInfo.SetPlatform
keywords: NSPocketDeviceInfo, GetPlatform
so.topic: reference
---

# SetPlatform(Integer platform)

What platform does this device belong to

**Parameter:** 
 - **platform** Integer
     - Enum: 0 = Apple 
     - Enum: 1 = Google 
     - Enum: 2 = Microsoft 
     - Enum: 3 = AppleDeveloper 
     - Enum: 4 = AppleAdHoc 
     - Enum: 5 = GoogleDeveloper 

```crmscript
NSPocketDeviceInfo thing;
Integer platform;
thing.SetPlatform(platform);
```

