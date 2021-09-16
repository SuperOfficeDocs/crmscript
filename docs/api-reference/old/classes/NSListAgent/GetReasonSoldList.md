---
uid: crmscript_ref_NSListAgent_GetReasonSoldList
title: NSReasonSold[] GetReasonSoldList(Integer[]  reasonSoldIds);
intellisense: NSListAgent.GetReasonSoldList
keywords: NSListAgent, GetReasonSoldList
so.topic: reference
---

# NSReasonSold[] GetReasonSoldList(Integer[]  reasonSoldIds);

Gets a vector of ReasonSold objects.

* **ReasonSoldIds** The identifiers of the NSReasonSold objects

**Returns:** NSReasonSold[]

```crmscript
Integer[] ids;
NSListAgent agent;
NSReasonSold[] res = agent.GetReasonSoldList(ids);
```
