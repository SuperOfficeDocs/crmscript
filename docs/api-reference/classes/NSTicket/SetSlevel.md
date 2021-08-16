---
uid: crmscript_ref_NSTicket_SetSlevel
title: SetSlevel(TicketSecurityLevel slevel)
intellisense: NSTicket.SetSlevel
keywords: NSTicket, GetSlevel
so.topic: reference
---

# SetSlevel(TicketSecurityLevel slevel)

The securitylevel of the ticket.

**Parameter:** 
 - **slevel** TicketSecurityLevel
     - Enum: 0 = Unknown 
     - Enum: 1 = Internal 
     - Enum: 2 = External 

```crmscript
NSTicket thing;
TicketSecurityLevel slevel;
thing.SetSlevel(slevel);
```

