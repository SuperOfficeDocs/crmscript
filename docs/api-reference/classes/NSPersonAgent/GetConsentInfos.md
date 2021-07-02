﻿---
uid: crmscript_ref_NSPersonAgent_GetConsentInfos
title: ConsentInfo[] GetConsentInfos(Integer personId)
intellisense: NSPersonAgent.GetConsentInfos
keywords: NSPersonAgent, GetConsentInfos
so.topic: reference
---

Get all consent information for a given person. May include withdrawn consents (check 

**Parameters:**
 - **personId** The person id to get consents for

**Returns:** List of consents recorded on this person

```crmscript
NSPersonAgent agent;
Integer personId;
ConsentInfo[] res = agent.GetConsentInfos(personId);
```

