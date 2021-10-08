---
uid: crmscript_ref_NSTicketMessageHeader_SetValue
title: Void SetValue()
intellisense: NSTicketMessageHeader.SetValue
keywords: NSTicketMessageHeader, SetValue
so.topic: reference
---

# Void SetValue()

The value of the header.

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
