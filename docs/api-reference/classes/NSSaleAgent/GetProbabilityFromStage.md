﻿---
uid: crmscript_ref_NSSaleAgent_GetProbabilityFromStage
title: Integer GetProbabilityFromStage(Integer stageId)
intellisense: NSSaleAgent.GetProbabilityFromStage
keywords: NSSaleAgent, GetProbabilityFromStage
so.topic: reference
---

Get the probability percentage for a given sale stage

**Parameters:**
 - **stageId** Probability list id

**Returns:** Integer

```crmscript
NSSaleAgent agent;
Integer stageId;
Integer res = agent.GetProbabilityFromStage(stageId);
```

