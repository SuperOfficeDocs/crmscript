---
uid: crmscript_ref_NSTicketMessageEntity_GetSlevel
title: TicketSecurityLevel GetSlevel()
intellisense: NSTicketMessageEntity.GetSlevel
keywords: NSTicketMessageEntity, GetSlevel
so.topic: reference
---

# TicketSecurityLevel GetSlevel()

The securitylevel of the message.

**Returns:** TicketSecurityLevel

     - Enum: 0 = Unknown 
     - Enum: 1 = Internal 
     - Enum: 2 = External 

```crmscript
NSTicketMessageEntity thing;
TicketSecurityLevel slevel  = thing.GetSlevel();
```

