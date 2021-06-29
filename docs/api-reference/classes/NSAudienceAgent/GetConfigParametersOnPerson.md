﻿---
uid: crmscript_ref_NSAudienceAgent_GetConfigParametersOnPerson
title: AudienceConfigParameter[] GetConfigParametersOnPerson(Integer personId)
intellisense: NSAudienceAgent.GetConfigParametersOnPerson
keywords: NSAudienceAgent, GetConfigParametersOnPerson
so.topic: reference
---

Gets the Audience configuration parameters belonging to the person specified

**Parameters:**
 - **personId** Id of the person the parameter belongs to

**Returns:** Array of Audience configuration parameters.

```crmscript
NSAudienceAgent agent;
Integer personId;
AudienceConfigParameter[] res = agent.GetConfigParametersOnPerson(personId);
```

