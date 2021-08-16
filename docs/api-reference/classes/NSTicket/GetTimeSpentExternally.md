---
uid: crmscript_ref_NSTicket_GetTimeSpentExternally
title: Integer GetTimeSpentExternally()
intellisense: NSTicket.GetTimeSpentExternally
keywords: NSTicket, GetTimeSpentExternally
so.topic: reference
---

# Integer GetTimeSpentExternally()

The total time (seconds) within the priority's office hours the ticket has been in a external waiting status (configurable), not including current state

**Returns:** Integer

```crmscript
NSTicket thing;
Integer timeSpentExternally  = thing.GetTimeSpentExternally();
```

