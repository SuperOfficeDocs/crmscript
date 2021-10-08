---
uid: crmscript_ref_NSTicketMessageHeader_SetName
title: Void SetName()
intellisense: NSTicketMessageHeader.SetName
keywords: NSTicketMessageHeader, SetName
so.topic: reference
---

# Void SetName()

The name of the header. This can for example be To, Cc or other custom headers that is set up in Service

**Returns:** Void

```crmscript
NSTicketAgent agent;
NSTicketMessage message = agent.GetTicketMessageEntity(12);
NSTicketMessageHeader[] headers ;
NSTicketMessageHeader to;
to.SetName("To");
to.SetValue("noreply@noreply.com");
headers.pushBack(to);

```
