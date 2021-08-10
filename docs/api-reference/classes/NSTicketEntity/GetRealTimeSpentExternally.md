---
uid: crmscript_ref_NSTicketEntity_GetRealTimeSpentExternally
title: Integer GetRealTimeSpentExternally()
intellisense: NSTicketEntity.GetRealTimeSpentExternally
keywords: NSTicketEntity, GetRealTimeSpentExternally
so.topic: reference
---

# Integer GetRealTimeSpentExternally()

The total time (seconds) within 24x7 the ticket has been in a external waiting status (configurable), not including current state

**Returns:** Integer

```crmscript
NSTicketEntity thing;
Integer realTimeSpentExternally  = thing.GetRealTimeSpentExternally();
```

