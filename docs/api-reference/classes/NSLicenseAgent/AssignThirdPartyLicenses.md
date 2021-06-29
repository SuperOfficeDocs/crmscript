﻿---
uid: crmscript_ref_NSLicenseAgent_AssignThirdPartyLicenses
title: ModuleLicenseLink[] AssignThirdPartyLicenses(Integer associateId, String moduleOwner, String[] moduleLicenseNames)
intellisense: NSLicenseAgent.AssignThirdPartyLicenses
keywords: NSLicenseAgent, AssignThirdPartyLicenses
so.topic: reference
---

Assign third party licenses

**Parameters:**
 - **associateId** User to assign third party licenses for
 - **moduleOwner** Name of the module owner to assign license for
 - **moduleLicenseNames** Name of module licenses to assign

**Returns:** All module license names assigned

```crmscript
NSLicenseAgent agent;
Integer associateId;
String moduleOwner;
String[] moduleLicenseNames;
ModuleLicenseLink[] res = agent.AssignThirdPartyLicenses(associateId, moduleOwner, moduleLicenseNames);
```

