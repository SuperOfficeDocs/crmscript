﻿---
uid: crmscript_ref_NSTicketPriorityEntity_SetTicketNewinfo
title: SetTicketNewinfo(Integer ticketNewinfo)
intellisense: NSTicketPriorityEntity.SetTicketNewinfo
keywords: NSTicketPriorityEntity, GetTicketNewinfo
so.topic: reference
---

This field indicates what to do with the escalation chain when the request gets new info

**Parameter:** 
 - **ticketNewinfo** Integer
     - Enum: -1 = None 
     - Enum: 0 = Stop 
     - Enum: 1 = Continue 
     - Enum: 2 = Restart 

```crmscript
NSTicketPriorityEntity thing;
Integer ticketNewinfo;
thing.SetTicketNewinfo(ticketNewinfo);
```

