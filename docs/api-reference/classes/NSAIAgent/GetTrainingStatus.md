---
uid: crmscript_ref_NSAIAgent_GetTrainingStatus
title: CategorizationStatusResponse GetTrainingStatus()
intellisense: NSAIAgent.GetTrainingStatus
keywords: NSAIAgent, GetTrainingStatus
so.topic: reference
---

# CategorizationStatusResponse GetTrainingStatus()

Calling the HugoAI endpoint to fetch the current training status.

**Returns:** Carrier to describe the current status of HugoAI categorization

```crmscript
NSAIAgent agent;
CategorizationStatusResponse res = agent.GetTrainingStatus();
```

