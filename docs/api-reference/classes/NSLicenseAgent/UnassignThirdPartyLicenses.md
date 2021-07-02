﻿---
uid: crmscript_ref_NSLicenseAgent_UnassignThirdPartyLicenses
title: ModuleLicenseLink[] UnassignThirdPartyLicenses(Integer associateId, String moduleOwner, String[] moduleLicenseNames)
intellisense: NSLicenseAgent.UnassignThirdPartyLicenses
keywords: NSLicenseAgent, UnassignThirdPartyLicenses
so.topic: reference
---

Unassign (remove) third party licenses

**Parameters:**
 - **associateId** User to unassign third party licenses for
 - **moduleOwner** Name of the module owner to unassign license for
 - **moduleLicenseNames** Name of module licenses to unassign (remove)

**Returns:** All module license names assigned

```crmscript
NSLicenseAgent agent;
Integer associateId;
String moduleOwner;
String[] moduleLicenseNames;
ModuleLicenseLink[] res = agent.UnassignThirdPartyLicenses(associateId, moduleOwner, moduleLicenseNames);
```

