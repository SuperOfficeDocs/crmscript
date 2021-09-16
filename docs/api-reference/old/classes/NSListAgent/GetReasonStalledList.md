---
uid: crmscript_ref_NSListAgent_GetReasonStalledList
title: NSReasonStalled[] GetReasonStalledList(Integer[]  reasonStalledIds);
intellisense: NSListAgent.GetReasonStalledList
keywords: NSListAgent, GetReasonStalledList
so.topic: reference
---

# NSReasonStalled[] GetReasonStalledList(Integer[]  reasonStalledIds);

Gets a vector of ReasonStalled objects.

* **ReasonStalledIds** The identifiers of the NSReasonStalled objects

**Returns:** NSReasonStalled[]

```crmscript
Integer[] ids;
NSListAgent agent;
NSReasonStalled[] res = agent.GetReasonStalledList(ids);
```
