---
uid: crmscript_ref_NSTicketEntity_SetConnectId
title: SetConnectId(Integer connectId)
intellisense: NSTicketEntity.SetConnectId
keywords: NSTicketEntity, GetConnectId
so.topic: reference
---

# SetConnectId(Integer connectId)

If a ticket is connected to another ticket, this field is set to the id of the &apos;master&apos; ticket.

**Parameter:** 
 - **connectId** Integer

```crmscript
NSTicketEntity thing;
Integer connectId;
thing.SetConnectId(connectId);
```

