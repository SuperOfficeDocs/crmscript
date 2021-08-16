---
uid: crmscript_ref_NSTicketEntity_GetTimeToReply
title: Integer GetTimeToReply()
intellisense: NSTicketEntity.GetTimeToReply
keywords: NSTicketEntity, GetTimeToReply
so.topic: reference
---

# Integer GetTimeToReply()

The time (minutes) between when the ticket was created and when it was replied to. Calculated based on priority&apos;s timeframe.

**Returns:** Integer

```crmscript
NSTicketEntity thing;
Integer timeToReply  = thing.GetTimeToReply();
```

