---
uid: crmscript_ref_NSWebhookAgent_GetLastError
title: String GetLastError(Integer webhookId)
intellisense: NSWebhookAgent.GetLastError
keywords: NSWebhookAgent, GetLastError
so.topic: reference
---

# String GetLastError(Integer webhookId)

Return the most recent error message received when calling this webhook.

**Parameters:**
 - **webhookId** Webhook to get error message for.

**Returns:** Error message, or empty string if no errors received

```crmscript
NSWebhookAgent agent;
Integer webhookId;
String res = agent.GetLastError(webhookId);
```

