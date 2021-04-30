﻿---
uid: crmscript_ref_NSAudienceAgent_GetAudienceLayoutOnPerson
title: AudienceLayoutEntity GetAudienceLayoutOnPerson(Integer personId)
intellisense: NSAudienceAgent.GetAudienceLayoutOnPerson
keywords: NSAudienceAgent, GetAudienceLayoutOnPerson
so.topic: reference
---

Gets the Audience layout belonging to the person specified.

**Parameters:**
 - **personId** The person id

**Returns:** Audience layout entity

```crmscript
NSAudienceAgent agent;
Integer personId;
AudienceLayoutEntity res = agent.GetAudienceLayoutOnPerson(personId);
```
