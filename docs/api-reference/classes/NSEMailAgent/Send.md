---
uid: crmscript_ref_NSEMailAgent_Send
title: NSEMailEntity[] Send(NSEMailEntity[] emails)
intellisense: NSEMailAgent.Send
keywords: NSEMailAgent, Send
so.topic: reference
---

Send the provided e-mails

**Parameters:**
 - **emails** The e-mails to send

**Returns:** The sent e-mails (updated with message id etc.)

```crmscript
NSEMailAgent agent;
NSEMailEntity[] emails;
NSEMailEntity[] res = agent.Send(emails);
```

