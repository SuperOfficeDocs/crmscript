---
uid: crmscript_ref_NSTicket_GetSlevel
title: TicketSecurityLevel GetSlevel()
intellisense: NSTicket.GetSlevel
keywords: NSTicket, GetSlevel
so.topic: reference
---

# TicketSecurityLevel GetSlevel()

The securitylevel of the ticket.

**Returns:** TicketSecurityLevel

     - Enum: 0 = Unknown 
     - Enum: 1 = Internal 
     - Enum: 2 = External 

```crmscript
NSTicket thing;
TicketSecurityLevel slevel  = thing.GetSlevel();
```

