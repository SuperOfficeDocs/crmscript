---
uid: crmscript_ref_NSModuleLicense_SetExtraFlags
title: SetExtraFlags(Integer extraFlags)
intellisense: NSModuleLicense.SetExtraFlags
keywords: NSModuleLicense, GetExtraFlags
so.topic: reference
---

# SetExtraFlags(Integer extraFlags)

Unspecified extra flags of license, part of checksum. Value=1 means this a 'user plan'; such licenses cause the admin gui to switch to radiobutton view

**Parameter:** 
 - **extraFlags** Integer

```crmscript
NSModuleLicense thing;
Integer extraFlags;
thing.SetExtraFlags(extraFlags);
```

